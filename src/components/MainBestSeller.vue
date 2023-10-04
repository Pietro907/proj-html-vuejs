
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


  </div>

</template>


<style scoped>

.featured > .title {
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


/* Color */
</style>