
<script>
export default {
    name: 'HeaderTop',
    data() {
        return {
            navMenuTop: [
                {
                    id: 1,
                    name: 'Shopping Cart'
                },
                {
                    id: 2,
                    name: 'My Account'
                },
                {
                    id: 3,
                    name: 'Cart'
                },

            ],
            brandsTop: [
                {
                    icon: 'fa-brands fa-facebook-f'
                },
                {
                    icon: 'fa-solid fa-brands fa-twitter'
                },
                {
                    icon: 'fa-solid fa-brands fa-instagram'
                },
                {
                    icon: 'fa-solid fa-brands fa-youtube'
                },
            ]
        }
    }
}
</script>



<template>
    <div class="container">
        <div class="row r_60 d_flex jst_btw">

            <div class="col">
                <div class="card brands_logo">

                    <i v-for="(brand, index) in brandsTop" :class="brand.icon"></i>
                    <!-- <i class="fa-solid fa-brands fa-twitter"></i>
                    <i class="fa-solid fa-brands fa-instagram"></i>
                    <i class="fa-solid fa-brands fa-youtube"></i> -->

                </div>
            </div>


            <div class="col d_flex jst_end">
                
                <div class="card menu_shopping">

                    <a href="#">{{ navMenuTop[0].name }}</a>
                    <a class="border_account" href="#">{{ navMenuTop[1].name }} <i class="fa-solid fa-angle-down"></i></a>

                </div>

                <div class="card cart bg_gray_light">

                    <i class="fa-solid fa-cart-shopping"></i>
                    <a href="#">{{ navMenuTop[2].name.toUpperCase() }}<i class="fa-solid fa-angle-down"></i></a>

                </div>
            </div>

        </div>
    </div>
</template>


<style scoped>
.container {
    border-bottom: 1px solid var(--bg-white-smoke);
    font-size: small;
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

.menu_shopping>a {
    padding: 1rem 0.5rem;
    text-decoration: none;
    color: var(--bg-gray-light);

    & i {
        font-size: 8px;
    }
}

.cart>a {
    color: var(--bg-secondary);
    padding: 1rem 0.5rem;
    text-decoration: none;

}

.col>.card {
    padding: 1rem 0;
}

.col>.cart {
    padding: 1rem 2.5rem;
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
}
</style>