
<script>
export default {
    name: 'HeaderBottom',
}
</script>



<template>

    <div class="container">
        <div class="row r_60 d_flex jst_btw">

            <div class="col">
                <div class="card">
                   <img class="logo_shop" src="../assets/img/classic shop/classic_shop_logo2x.png" alt="">
                </div>
            </div>
            <div class="col">
                <div class="card brands_logo">
                   menu nav
                </div>
            </div>
            <div class="col">
                <div class="card brands_logo">
                   button:hover & icon
                </div>
            </div>
        </div>
    </div>

</template>


<style scoped>

.container {
    font-size: xx-small;
}

.r_60 {
    width: 60%;
    margin: 0 auto;
}

.col {
    width: calc(100% / 12 * 6);
}
.logo_shop {
    width: 130px;
}

</style>