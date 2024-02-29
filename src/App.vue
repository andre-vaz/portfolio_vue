<template>
  <!-- <Navbar />
  <Footer />
  <router-view></router-view> -->

  <div id="app">
    <Navbar />
    <div class="content">
      <router-view></router-view>
    </div>
    <Footer />
  </div>
  
</template>

<script>
import Navbar from './components/NavBar.vue';
import Footer from './components/footer.vue';

export default {
  components: {
    Navbar,
    Footer
  }
};
</script>

<style>
  @import "./assets/fonts/fonts.css";
  @import "./assets/styles/main.css";

  #app {
    display: flex;
    flex-direction: column;
    min-height: 100vh; /* Ensure that the layout takes up at least the full viewport height */
  }

  .content {
    flex: 1; /* Expand to fill the remaining space */
  }
</style>
