
<script>
export default {
    name: 'MainCollection',
}
</script>

<template>
    <div class="container collections">
        <div class="row d_flex">

            <div class="col">
                <div class="card overview">

                    <img src="../assets/img/collections/winter_collection_bg.jpg" alt="">

                    <div class="card collect d_flex f_column align_center">

                        <h2>Winter Collection</h2>
                        <p>STYLISH AND WARM</p>

                        <div class="btn">

                            <button class="color" type="button">VIEW MORE</button>

                        </div>

                    </div>
                </div>
            </div>

            <div class="col">
                <div class="card overview">
                    <img src="../assets/img/collections/spring/spring_collection_bg.jpg" alt="">

                    <div class="card collect d_flex f_column align_center">

                        <h2>Spring Collection</h2>
                        <p>BRIGHT AND COLORFUL</p>

                        <div class="btn">

                            <button class="color" type="button">VIEW MORE</button>

                        </div>

                    </div>

                </div>
            </div>

            <div class="col">
                <div class="card overview">
                    
                    <img src="../assets/img/collections/autumn_collection_bg.jpg" alt="">

                    <div class="card collect d_flex f_column align_center">

                        <h2>Autumn Collection</h2>
                        <p>RICH AND CONFORTABLE</p>

                        <div class="btn">

                            <button class="color" type="button">VIEW MORE</button>

                        </div>

                    </div>

                </div>
            </div>

        </div>
    </div>

</template>


<style scoped>
.card>img {
    width: 100%;
}

.overview {
    position: relative;
}

.collect {
    height: 430px;
    padding: 0 0 5rem;
    text-align: center;
    margin: 2rem 0 0;
    position: absolute;
    top: 280px;
    left: 110px;

    & h2 {
        color: var(--bg-primary);
        font-size: 35px;
        margin: 0 0 0.5rem
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

.bg_gray_light {
    background-color: var(--bg-white-smoke);
}

.color {
    background-color: #f5f5f523;
}
</style>