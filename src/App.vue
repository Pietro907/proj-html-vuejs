<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default{
  components: {
    Header,
    Main,
    Footer,
  },
  data(){
    return {

    }
  }


}


</script>

<template>
  <h1><i class="fa fa-clipboard" aria-hidden="true"></i></h1>
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
