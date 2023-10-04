
<script>
export default {
  name: 'MainBestSeller',

}
</script>

<template>
  <div class="featured d_flex jst_center align_center">

    <div class="line_gray"></div>

    <div class="title">

      <h2>Best Seller</h2>
      <p>Must have produtcs from our top sellers</p>

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
          <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">
        </div>

        <div class="card">
          <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">
        </div>

        <div class="card">
          <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">
        </div>

        <div class="card">
          <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket.jpg" alt="">
        </div>

        <div class="card">
          <button class="next" type="button"><i class="fa-solid fa-angle-right"></i></button>
        </div>

      </div>

    </div>

    <div class="container offers">
      <div class="row">

        <div class="col d_flex jst_center align-center">
          <div class="card overview mx_1">

            <img src="../assets/img/promotion/promo_box_1_bg.jpg" alt="">

            <div class="card collect d_flex f_column align_center">
              
              <div class="title">

                <h2>70% Off</h2>
                <p>Vivamus tempor leo lacus, feugiat <br> ut magna aliquam erat</p>

              </div>


              <div class="btn">

                <button class="color" type="button">VIEW MORE</button>

              </div>
            </div>

          </div>

          <div class="card overview mx_1">

            <img src="../assets/img/promotion/promo_box_2_bg.jpg" alt="">

            <div class="card collect d_flex f_column align_center">

              <div class="title">

                <h2>Free Shipping</h2>
                <p>Vivamus tempor leo lacus, feugiat <br> ut magna aliquam erat</p>

              </div>


              <div class="btn">

                <button class="color" type="button">VIEW MORE</button>

              </div>
            </div>

          </div>

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
    padding: 0.5rem 0 0;
  }
}

.line_gray {
  background-color: var(--bg-gray-light);
  height: 0.5px;
  width: 20%;
  margin: 0 5rem;
}

.carosello>.card>img {
  width: 200px;
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

.offers {
  background-image: url(../assets/img/bkgd_confetti-compressor.jpg);
  background-size: cover;
  background-position: right;
  padding: 3rem;
}

.collect {

  height: 430px;
  padding: 0 0 5rem;
  margin: 4rem 0 0;
  position: absolute;
  top: 20px;
  left: 40px;

  & h2 {
    color: var(--bg-primary);
    font-size: 35px;
  }

  & p {
    color: var(--bg-white-smoke);
    font-size: 15px;
    margin: 0 0 1.5rem
  }
}

.btn>button {
  font-size: 9px;
  padding: 0.6rem 1.5rem;
  border-radius: 20px;
  border-color: var(--bg-primary);
  color: var(--bg-primary);
  margin: 0 8rem 0 0;
}

.overview {
  position: relative;
}

.card>img {
  width: 450px;
}


/* Utilities */
.d_flex {
  display: flex;
}

.f_row {
  flex-direction: row;
}

.f_column {
  flex-direction: column;
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

.mx_1 {
  margin: 0 1rem;
}

/* Color */

.color {
  background-color: #f5f5f523;
}
</style>