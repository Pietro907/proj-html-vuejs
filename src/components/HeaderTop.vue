
<script>
export default {
    name: 'HeaderTop',

}
</script>



<template>
    <div class="container">
        <div class="row r_80 d_flex jst_btw">

            <div class="col">
                <div class="card brands_logo">

                    <div class="fa-solid fa-brands fa-facebook"></div>
                    <div class="fa-solid fa-brands fa-twitter"></div>
                    <div class="fa-solid fa-brands fa-instagram"></div>
                    <div class="fa-solid fa-brands fa-youtube"></div>

                </div>
            </div>




            <div class="col d_flex jst_end">
                <div class="card">

                    <a href="#">Shopping Cart</a>
                    <a href="#">My Acoount <i class="fa-solid fa-angle-down"></i></a>

                </div>

                <div class="card">

                    <div class="fa-solid fa-cart-shopping"></div>
                    <a href="#">Cart <i class="fa-solid fa-angle-down"></i></a>


                </div>
            </div>

        </div>
    </div>
</template>


<style scoped>
.r_80 {
    width: 60%;
    margin: 0 auto;
}
.col {
    width: calc(100% / 12 * 6);
}
.card {
    background-color: var(--bg-primary);
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

.align_self_end {
    align-self: self-end;
}
</style>