<template>
  <div id="app">
    <Monster msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
import Monster from "./components/Monster.vue";

export default {
  name: "App",
  components: {
    Monster,
  },
};
</script>
<style>
* {
  box-sizing: border-box;
}

html {
  font-family: "Kiwi Maru", serif;
}

body {
  margin: 0;
}
</style>
