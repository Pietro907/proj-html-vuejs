
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
                    <a href="#">My Acoount <i class="fa-solid fa-angle-down"></i></a>

                </div>

                <div class="card menu_shopping">

                    <i class="fa-solid fa-cart-shopping"></i>
                    <a href="#">Cart <i class="fa-solid fa-angle-down"></i></a>


                </div>
            </div>

        </div>
    </div>
</template>


<style scoped>
.container{
    padding: 1rem 0;
    border-bottom: 1px solid var(--bg-white-smoke);
}
.r_60 {
    width: 60%;
    margin: 0 auto;
}
.col {
    width: calc(100% / 12 * 6);
}
.brands_logo{
    color: var(--bg-secondary);
}
.brands_logo > i {
    padding: 0 0.5rem;
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