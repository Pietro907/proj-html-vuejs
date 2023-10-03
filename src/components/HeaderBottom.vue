
<script>
export default {
    name: 'HeaderBottom',
}
</script>



<template>
    <div class="container">
        <div class="row r_60 d_flex jst_btw align_center">

            <div class="col">
                <div class="card">
                    <img class="logo_shop" src="../assets/img/classic shop/classic_shop_logo2x.png" alt="">
                </div>
            </div>
            <div class="col">
                <div class="card nav_elemets">

                    <nav>

                        <a href="#">Home <i class="fa-solid fa-angle-down"></i></a>
                        <a href="#">Shop <i class="fa-solid fa-angle-down"></i></a>
                        <a href="#">Products <i class="fa-solid fa-angle-down"></i></a>
                        <a href="#">Categories <i class="fa-solid fa-angle-down"></i></a>
                        <a href="#">News</a>
                        <a href="#">Elements <i class="fa-solid fa-angle-down"></i></a>

                    </nav>

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
    padding: 2rem 0;
}

.col {
    width: calc(100% / 12 * 6);
}

.logo_shop {
    width: 130px;
}
.nav_elemets > nav > a {
    text-decoration: none;
    color: var(--bg-gray-light);
}


/* Utilities */
.d_flex {
    display: flex;
}

.jst_center {
    justify-content: center;
}

.jst_end {
    justify-content: end;
}

.jst_btw {
    justify-content: space-between;
}

.align_center {
    align-items: center;
}
</style>