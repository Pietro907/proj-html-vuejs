
<script>
export default {
  name: 'MainBestSeller',

}
</script>

<template>
  <div class="featured">

    <h2>Best Seller</h2>
    <p>Must have produtcs from our top sellers</p>

  </div>
</template>


<style scoped>

.featured {
    text-align: center;
    margin: 6rem 0;
    & h2 {
        font-size: 29px;
    }
    & p { 
        font-size: 12px;
        color: var(--bg-gray-light);
        padding: 0.5rem 0 0
    }
}

</style>