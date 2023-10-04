
<script>
import FooterSponsor from './FooterSponsor.vue';
import FooterSubscribe from './FooterSubscribe.vue';
import FooterAvadaShop from './FooterAvadaShop.vue';
import FooterCopyright from './FooterCopyright.vue';

    export default {
        name: 'Footer',
        data(){
            return {

            }
        },
        components: {
            FooterSponsor,
            FooterSubscribe,
            FooterAvadaShop,
            FooterCopyright,
        }
    }
</script>


<template>
    
    <FooterSponsor />

    <FooterSubscribe />

    <FooterAvadaShop />

    <FooterCopyright />

</template>



<style scoped>

</style>