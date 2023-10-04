
<script>
import MainJumbotron from './MainJumbotron.vue';
import MainFeaturedProduction from './MainFeaturedProduction.vue';
import MainCollection from './MainCollection.vue';
import MainBestSeller from './MainBestSeller.vue';
import MainNewArrivals from './MainNewArrivals.vue';
import MainTestimonial from './MainTestimonial.vue';
import MainFromOurBlog from './MainFromOurBlog.vue';
import MainTopRates from './MainTopRates.vue';

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
            MainTestimonial,
            MainFromOurBlog,
            MainTopRates,
        }
    }
</script>


<template>
    
    <MainJumbotron />
    
    <MainFeaturedProduction />

    <MainCollection />

    <MainBestSeller />

    <MainNewArrivals />

    <MainTestimonial />

    <MainFromOurBlog />

    <MainTopRates />

</template>



<style scoped>



</style>