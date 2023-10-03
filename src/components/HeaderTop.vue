
<script>
export default {
    name: 'HeaderTop',

}
</script>



<template>
    <div class="container">
        <div class="row r_60 d_flex jst_btw">

            <div class="col">
                <div class="card brands_logo">

                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-solid fa-brands fa-twitter"></i>
                    <i class="fa-solid fa-brands fa-instagram"></i>
                    <i class="fa-solid fa-brands fa-youtube"></i>

                </div>
            </div>


            <div class="col d_flex jst_end">
                <div class="card menu_shopping">

                    <a href="#">Shopping Cart</a>
                    <a class="border_account" href="#">My Account <i class="fa-solid fa-angle-down"></i></a>

                </div>

                <div class="card cart bg_gray_light">

                    <i class="fa-solid fa-cart-shopping"></i>
                    <a href="#">CART <i class="fa-solid fa-angle-down"></i></a>

                </div>
            </div>

        </div>
    </div>
</template>


<style scoped>
.container {
    border-bottom: 1px solid var(--bg-white-smoke);
    font-size: x-small;
}

.r_60 {
    width: 60%;
    margin: 0 auto;
}

.col {
    width: calc(100% / 12 * 6);
}

.brands_logo,
.menu_shopping>i,
.cart {
    color: var(--bg-secondary);
}

.brands_logo>i {
    padding: 0 0.5rem;
}

.menu_shopping>i {
    padding: 0 0 0 4rem;
}

.menu_shopping>a,
.cart>a {
    padding: 1rem 0.5rem;
    text-decoration: none;
    color: var(--bg-gray-light);
}

.cart>a {
    color: var(--bg-secondary);
}

.col>.card {
    padding: 1rem 0;
}

.col>.cart {
    padding: 1rem 3rem;
}

.card {
    background-color: var(--bg-primary);
}

.border_account {
    border-left: 1px solid var(--bg-white-smoke);
    border-right: 1px solid var(--bg-white-smoke);
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


/* Color */

.bg_gray_light {
    background-color: var(--bg-white-smoke);
}</style>