<template>
  <div id="app" class="h-screen bg-yellow-300">
    <Navigation />
    <Profile />
  </div>
</template>

<script>
import Navigation from "./components/nav/Navigation";
import Profile from "./components/profile/Profile";

export default {
  name: "App",
  components: {
    Navigation,
    Profile
  }
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}
</style>
