
<script>
export default {
    name: 'FooterCopyright',
}
</script>

<template>
    <div class="container">
        <div class="row r_60 d_flex jst_center">

            <div class="col">
                <div class="card d_flex jst_center">

                    <p><i class="fa-regular fa-copyright"></i> Copyright 2021 - 2020 |</p>
                    <p class="ps_05">Avada Theme by Theme Fusion | </p>
                    <p class="ps_05">Powered by WordPress </p>

                </div>
                <div class="card d_flex jst_center">
                    <img src="../assets/img/payment_cards_footer.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.container {
    background-color: var(--bg-footer-copy);
    height: 100px;
    color: var(--bg-white-smoke);
}

.r_60 {
    width: 60%;
    margin: 0 auto;
    padding: 1rem 0;
}

.card>p {
    padding: 0 0 0.8rem;
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


.brd_rght {
    border-right: 1px solid var(--bg-white-smoke);

}




/* Color */


/* Spacing */
.ps_05 {
    margin-left: 0.3rem;
}
</style>