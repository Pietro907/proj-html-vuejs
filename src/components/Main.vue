
<script>
import MainJumbotron from './MainJumbotron.vue';
import MainFeaturedProduction from './MainFeaturedProduction.vue';
import MainCollection from './MainCollection.vue';
import MainBestSeller from './MainBestSeller.vue';
import MainNewArrivals from './MainNewArrivals.vue';

    export default {
        name: 'Main',
        data(){
            return {

            }
        },
        components: {
            MainJumbotron,
            MainFeaturedProduction,
            MainCollection,
            MainBestSeller,
            MainNewArrivals,
        }
    }
</script>


<template>
    
    <MainJumbotron />
    
    <MainFeaturedProduction />

    <MainCollection />

    <MainBestSeller />

    <MainNewArrivals />

</template>



<style scoped>



</style>