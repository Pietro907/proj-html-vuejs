<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import state from './state.js';

export default{
  components: {
    Header,
    Main,
    Footer,
  },
  data(){
    return {
      state,
    }
  }


}


</script>

<template>

<!-- Header -->
<Header />
<!-- Main -->
<Main />
<!-- Footer -->
<Footer />

</template>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


</style>
