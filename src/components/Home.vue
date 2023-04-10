<template>
  <Navbar />
  <Header />

  <About />

<br>


  <Footer />

</template>

<script>
import Navbar from "./Navbar.vue";
import Header from "./Header.vue";

import About from "./About.vue";


import Footer from "./Footer.vue";

export default {
  name: "Home",
  data() {
    return {};
  },

  props: {
    blog: Array,
  },

  components: {
    Navbar,
    Header,
  
    About,
 
  
    Footer,
  },
};
</script>

<style>
#isiaja{
  background-image: linear-gradient(60deg, #FFDE59 0%, #FFDE59 100%);
}
</style>
