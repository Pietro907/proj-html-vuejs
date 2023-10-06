

<script>
export default {
    name: 'MainFeaturedProduction',
}
</script>




<template>
    <div class="featured d_flex jst_center align_center">

        <div class="line_gray"></div>

        <div class="title">

            <h2>Featured Products</h2>
            <p>Must have produtcs from our top sellers</p>

        </div>

        <div class="line_gray"></div>

    </div>

    <!-- Schede categoria previsto Active al click e cambio card:hover in base alla categoria  -->
    <div class="category d_flex jst_center align_center">

        <a>Men</a>
        <a>Women</a>
        <a>Accessories</a>

    </div>



    <div class="container">
        <div class="row r_60 d_flex jst_center align_center">

            <!-- Colonna img hover -->
            <div class="col">

                <div class="card products">

                    <img class="first_img" src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">

                    <div class="hover_img">
                        <img class="first_img2" src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg"
                            alt="">

                        <i class="fa-regular fa-check-square"></i>
                    </div>

                    <div class="info_cost">

                        <h5>Black Leather Jacket</h5>
                        <h6>Men, Jackets, Jeans</h6>
                        <p class="style_line">$235</p>
                        <p>$200</p>

                    </div>

                </div>
            </div>

            <!-- Colonna img hover -->
            <div class="col">
                <div class="card products">

                    <img class="first_img" src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg"
                        alt="">

                    <div class="hover_img">
                        <img class="first_img2" src="../assets/img/featured_produtcs/black_leather/black_leather_suit.jpg"
                            alt="">

                        <i class="fa-regular fa-check-square"></i>
                    </div>

                    <div class="info_cost">
                        <h5>Black Leather Suit</h5>
                        <h6>Men, Jackets</h6>
                        <p>$176</p>
                    </div>

                </div>
            </div>

            <!-- Colonna img hover -->
            <div class="col">

                <div class="card products">

                    <img class="first_img"
                        src="../assets/img/featured_produtcs/blue_jacket/blue_jacket_and_white_stripe_tee.jpg" alt="">

                    <div class="hover_img">

                        <img class="first_img2"
                            src="../assets/img/featured_produtcs/blue_jacket/blue_jacket_and_white_stripe_tee.jpg" alt="">

                        <i class="fa-regular fa-check-square"></i>

                    </div>

                    <div class="info_cost">
                        <h5>Blue Jacket & Stripe Tee</h5>
                        <h6>Men, Jackets, Suits</h6>
                        <p>$580</p>
                    </div>

                </div>
            </div>

            <!-- Colonna img hover -->
            <div class="col">
                <div class="card products">

                    <img class="first_img" src="../assets/img/featured_produtcs/modern_black/modern_black_leather_suit.jpg"
                        alt="">

                    <div class="hover_img">

                        <img class="first_img2"
                            src="../assets/img/featured_produtcs/modern_black/modern_black_leather_suit.jpg" alt="">

                        <i class="fa-regular fa-check-square"></i>

                    </div>

                    <div class="info_cost">
                        <h5>Modern Black Leather Suit</h5>
                        <h6>Men, Jackets</h6>
                        <p>$96</p>
                    </div>


                </div>
            </div>

        </div>
    </div>
</template>



<style scoped> .featured>.title {
     text-align: center;
     margin: 6rem 0 2rem;

     & h2 {
         font-size: 35px;

     }

     & p {
         font-size: 15px;
         padding: 0.5rem 0 0;
         color: var(--bg-gray-light);
     }
 }

 .line_gray {
     background-color: var(--bg-gray-light);
     height: 0.5px;
     width: 20%;
     margin: 2rem 5rem -0.5rem;
 }

 .category>a {
     background-color: var(--bg-primary);
     padding: 1rem 2.5rem;
     border: 1px solid var(--bg-gray-light);
 }

 .category>a:hover {
     background-color: var(--bg-gray-light);
 }

 .r_60 {
     width: 60%;
     margin: 0 auto;
     padding: 2rem 0;
 }

 .card {
     position: relative;
 }

 .products>img,
 .hover_img>.first_img,
 .hover_img>.first_img2 {
     width: 230px;
     object-fit: contain;
 }

 .hove_img {
     position: absolute;
     top: 0;
     right: 0;
     height: 100%;
     width: 100%;
     opacity: 0;
     transition: .5s ease;
 }

 .card:hover .first_img {
     opacity: 0.3;
     display: none;
 }

 .card:hover .first_img2 {
     opacity: 0.3;
 }

 .first_img:hover {
     display: none;
 }

 .card:hover .hover_img {
     display: block;
     height: 299px;
     width: 230px;
     background-color: rgba(0, 255, 255, 0.635);
     margin: 0 0 0.2rem;
     opacity: 0.9;
 }

 .card .hover_img {
     display: none;
 }

 .hover_img>i {
     background-color: var(--bg-footer-copy);
     color: var(--bg-primary);
     padding: 1rem;
     border-radius: 50%;
     position: absolute;
     top: 40%;
     left: 50%;
     transform: translate(-50%, -50%);
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
 }</style>