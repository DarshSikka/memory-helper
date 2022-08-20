<template>
  <div>
    <Navbar />
    <router-view />
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  background: skyblue;
}
nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: white;
    &.router-link-exact-active {
      color: #0bdb07;
    }
  }
}
</style>
<script>
import Navbar from "./components/Navbar.vue";
export default {
  name: "App",
  components: {
    Navbar,
  },
};
</script>
