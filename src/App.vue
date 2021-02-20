<template>
  <div id="app">
    <Navbar />

    <router-view></router-view>

    <Footer />
  </div>
</template>


<script>
import Navbar from "./views/Header";
import Footer from "./views/Footer";

export default {
  components: {
    Navbar,
    Footer,
  },
};
</script>
<style>
#app {
  color: #000000;
  font-family: "Anonymous Pro", monospace;
}
</style>
