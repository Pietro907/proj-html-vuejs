
<script>
import MainJumbotron from './MainJumbotron.vue';
import MainFeaturedProduction from './MainFeaturedProduction.vue';
import MainCollection from './MainCollection.vue';

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
        }
    }
</script>


<template>
    
    <MainJumbotron />
    
    <MainFeaturedProduction />

    <MainCollection />

</template>



<style scoped>



</style>