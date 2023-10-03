
<script>
import HeaderTop from './HeaderTop.vue';
import HeaderBottom from './HeaderBottom.vue';

    export default {
        name: 'Header',
        components:{
            HeaderTop,
            HeaderBottom,
        },
        data(){
            return {

            }
        }
    }
</script>


<template>
 
    <HeaderTop />
    <HeaderBottom />

</template>



<style scoped>

</style>