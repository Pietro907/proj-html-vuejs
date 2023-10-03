<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';
import {state} from './state.js';


export default{
  name: 'App',
  data(){
    return {
      state,
    }
  },
  components: {
    Header,
    Main,
    Footer,
  },


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

/* Color */
:root{
  --bg-primary: #FFFFFF;
  --bg-secondary: #494949;
  --bg-gray-light: #AAAAAA;
  --bg-blue-light: #427ED1;
  --bg-heaven: #55CCE5;
  --bg-white-smoke: #F5F5F5;
}

</style>
