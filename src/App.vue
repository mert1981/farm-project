<template>
  <div id="app" class="flex flex-row max-h-screen space-x-4">
    <div class="w-1/12 bg-gray-500 h-screen">
      <sideBar />
    </div>
    <div class="w-11/12 bg-gray-700 h-screen">
      <router-view />
    </div>
  </div>
</template>
<script>
import sideBar from "./components/side-bar.vue";
export default {
  name: "app",
  components: { sideBar },
};
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
