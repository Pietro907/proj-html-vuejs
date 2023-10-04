

<script>
export default {
    name: 'FooterSubscribe',
}
</script>

<template>
    <div class="container d_flex jst_center align_center">
        <div class="row r_60 d_flex jst_btw">

            <div class="col subscribe d_flex jst_center align_center">

                <div class="card icon_email">
                    <i class="fa-regular fa-envelope"></i>
                </div>

                <div class="card title">
                    <h3>Subscribe now and get special offers</h3>
                </div>

            </div>

            <div class="col d_flex jst_center align_center">

                <div class="card input_email">
                    <input type="email" value="" placeholder="Insert your email">
                </div>
                <div class="card btn_shop_now">
                    <button type="button">Send</button>
                </div>

            </div>

        </div>
    </div>

   


    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
    <h1>SUBSCRIBE</h1>
</template>

<style scoped>


.container {
    background: var(--bg-footer-sub);
    height: 220px;
}

.subscribe {
    font-size: 22px;
}

.icon_email {
    background-color: var(--bg-footer-copy);
    color: var(--bg-gray-light);
    margin: 0 1rem 0 0;
    padding: 1rem;
    border-radius: 50%;
}

.title {
    color: var(--bg-primary);
}
.input_email > input {
    width: 250px;
    margin: 0 1rem 0 0;
    padding: 0.7rem 1rem 0.7rem 1rem ;
    border-radius: 20px;
    text-align: start;
    font-size: xx-small;
}
.btn_shop_now>button {
    padding: 0.5rem 1rem;
    border-radius: 20px;
    font-size: xx-small;
    background-color: var(--bg-blue-light);
    border-color: var(--bg-blue-light);
    color: var(--bg-white-smoke);
}



/* Utilities */
.d_flex {
    display: flex;
}
.r_60 {
    width: 60%;
    margin: 0 auto;
    padding: 1rem 0;
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