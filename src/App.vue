<template>
  <div id="app">
    <SideBar/>
    <router-view />
  </div>
</template>

<style lang="scss">
@import url("https://fonts.googleapis.com/css2?family=Ubuntu:wght@400;500&display=swap");

// Цвета типографики
$text-black: #5c5c5c;
$text-white: #ffffff;
$text-gray: #a3a3a3;
$text-gray--light: #a5a5a5;

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: Ubuntu, sans-serif;
  color: $text-black;
}
</style>

<script>
// @ is an alias to /src
import SideBar from '@/components/SideBar.vue'

export default {
  components: {
    SideBar
  }
}
</script>
