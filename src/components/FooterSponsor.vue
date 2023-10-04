

<script>
export default {
    name: 'FooterSponsor',
}
</script>

<template>

    <div class="container">
        <div class="row r_60">

            <h4>BRANDS LOGO</h4>

            <div class="col title d_flex jst_btw">

                <div class="card">
                    <img src="../assets/img/logo/b_logotype_6.png" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/logo/b_logotype_7.png" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/logo/b_logotype_1.png" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/logo/b_logotype_2.png" alt="">
                </div>

                <div class="card">
                    <img src="../assets/img/logo/b_logotype_3.png" alt="">
                </div>

            </div>
        </div>
    </div>

</template>


<style scoped>

.container {
    background-color: var(--bg-white-smoke);
    padding-bottom: 1rem;
}

.r_60 {
    width: 60%;
    margin: 0 auto;
    padding: 2rem 0;
}
.row>h4 {
    text-align: center;
    color: var(--bg-gray-light);
    padding: 2rem 0;
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