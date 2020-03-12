<template>
  <div id="app">
    <div class="container">
      <Header />
      <Navbar />
      <Profile />
    </div>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Navbar from './components/Navbar.vue'
import Profile from "./components/Profile/Profile";

export default {
  name: 'App',
  components: {
    Profile,
    Header,
    Navbar
  }
}
</script>

<style>
  #app {
    font-family: Avenir, Helvetica, Arial, sans-serif;
    font-size: 18px;
    color: #2c3e50;
  }

  a {
    text-decoration: none;
  }
  .container {
    display: grid;
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    grid-template-areas:
            "h h"
            "n c";
    grid-template-rows: 60px 1fr;
    grid-template-columns: 2fr 10fr;
    grid-gap: 10px;
  }
</style>
