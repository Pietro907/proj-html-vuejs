
<script>
import HeaderTop from './HeaderTop.vue';
import HeaderBottom from './HeaderBottom.vue';

    export default {
        name: 'Header',
      
        data(){
            return {

            }
        },
        components:{
            HeaderTop,
            HeaderBottom,
        },
    }
</script>


<template>
 
    <HeaderTop />
    <HeaderBottom />

</template>



<style scoped>

</style>