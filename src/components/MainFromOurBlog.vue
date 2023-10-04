

<script>
export default {
    name: 'MainFromOurBlog',
}
</script>

<template>
    <div class="featured d_flex jst_center align_center">

        <div class="line_gray"></div>

        <div class="title">

            <h2>From Our Blog</h2>
            <p>The latest Classic Shop news</p>

        </div>

        <div class="line_gray"></div>

    </div>

    <div class="container">
        <div class="row r_60 d_flex jst_center align_center">

            <div class="col">
                <div class="card products">
                    <img src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg" alt="">

                    <div class="info_cost">
                        <h5>Black Leather Suit</h5>
                        <h6>Men, Jackets</h6>
                        <p>$176</p>
                    </div>

                </div>
            </div>

            <div class="col">
                <div class="card products">
                    <img src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg" alt="">

                    <div class="info_cost">
                        <h5>Black Leather Suit</h5>
                        <h6>Men, Jackets</h6>
                        <p>$176</p>
                    </div>

                </div>
            </div>

            <div class="col">
                <div class="card products">
                    <img src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg" alt="">

                    <div class="info_cost">
                        <h5>Black Leather Suit</h5>
                        <h6>Men, Jackets</h6>
                        <p>$176</p>
                    </div>

                </div>
            </div>

        </div>
    </div>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
</template>

<style scoped>
.featured>.title {
    text-align: center;
    margin: 6rem 0;

    & h2 {
        font-size: 29px;
        padding: 0.5rem 0;
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
.r_60 {
     width: 60%;
     margin: 0 auto;
     padding: 2rem 0;
 }

 .products>img {
     width: 230px;
 }

 .info_cost>h5 {
     padding: 1rem 0 0.5rem;
 }

 .info_cost>h6 {
     color: var(--bg-gray-light);
 }

 p {
     display: inline-block;
     padding: 0.5rem 0.5rem 0 0;
     font-size: 12px;
     color: var(--bg-heaven);
 }

 .style_line {
     text-decoration-line: line-through;
     font-size: 9px;
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