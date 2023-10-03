
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
<!-- Divisione Header in Top & Bottom -->
    <HeaderTop />

    <HeaderBottom />

</template>



<style scoped>

</style>