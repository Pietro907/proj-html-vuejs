
<script>

export default {
    name: 'MainNewArrivals',

}



</script>


<template>
    <div class="featured d_flex jst_center align_center">

        <div class="line_gray"></div>

        <div class="title">

            <h2>New Arrivals</h2>
            <p>Brand new products from top designers</p>

        </div>

        <div class="line_gray"></div>

    </div>

    <div class="container">
        <div class="row">
            <div class="col carosello d_flex jst_center align_center">

                <div class="card">
                    <button class="prev" type="button"><i class="fa-solid fa-angle-left"></i></button>
                </div>

                <div class="card">
                    <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/hipster_black/hipster_black_top.jpg" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/collections/spring/spring_printed_dress.jpg" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/modern/modern_love_tee.jpg" alt="">
                </div>

                <div class="card">
                    <button class="next" type="button"><i class="fa-solid fa-angle-right"></i></button>
                </div>

            </div>

        </div>

    </div>

</template>


<style scoped>
.featured>.title {
    text-align: center;
    margin: 6rem 0;

    & h2 {
        font-size: 29px;
    }

    & p {
        font-size: 12px;
        color: var(--bg-gray-light);
    }
}

.line_gray {
    background-color: var(--bg-gray-light);
    height: 0.5px;
    width: 20%;
    margin: 0 5rem 0.5rem;
}
.carosello>.card>img {
  width: 100%;
}

.prev,
.next {
  padding: 1rem 0.5rem;
  background-color: var(--bg-gray-light);
  border: none;
}

.prev>i,
.next>i {
  color: var(--bg-white-smoke);
  font-size: xx-small;
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
</style>