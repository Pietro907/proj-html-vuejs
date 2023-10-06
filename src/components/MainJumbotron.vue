
<script>


export default {
    name: 'MainJumbotron',
    data() {
        return {
            menuJumbo: [
                {
                    title: 'Brand New Arrivals'
                },
                {
                    titleMini: 'New Collection From New York'
                },
                {
                    titleBtn: [
                        {
                            name: 'View All',
                        },
                        {
                            name: 'Lookbook',
                        },
                    ],
                },
            ],

            bgJumbo: [
                {
                    image: 'src/assets/img/home1/home1_slide_three_bg_2.jpg'
                },
                {
                    image: 'src/assets/img/blue_leather/blue_leather_jacket.jpg'
                },
                {
                    image: 'src/assets/img/collections/winter_collection_bg.jpg'
                },
                {
                    image: 'src/assets/img/hipster_black/hipster_black_top.jpg'
                },
            ],
        

            /* methods: {
                getImageUrl() {
                    return new URL(`../assets/img/${menuJumob.bgJumbo[1]}`);
                },
            },
            computed: {
                ImageNow() {
                    return this.image[Math.abs(this.currentBgImage) % this.image.length];
                },
            }, */

        }
    }
}

</script>


<template>
    <!-- Qui background-image! in .container -->
    <div class="container">

        <img class="bg_img" :src="bgJumbo[0].image" alt="">
        <div class="row">

            <!-- Colonna titolo centro image -->
            <div class="col d_flex jst_center">

                <!-- Card centro image -->
                <div class="card new_arrivals d_flex f_column jst_center">

                    <!-- Titolo e Sottotitolo -->
                    <h1>{{ menuJumbo[0].title }}</h1>
                    <h5>{{ menuJumbo[1].titleMini.toUpperCase() }}</h5>

                    <!-- Button -->
                    <div class="btn">

                        <!-- Btn sx -->
                        <button class="color m_05" type="button">{{ menuJumbo[2].titleBtn[0].name.toUpperCase()
                        }}</button>
                        <!-- Btn dx -->
                        <button class="color m_05" type="button">{{ menuJumbo[2].titleBtn[1].name.toUpperCase()
                        }}</button>

                    </div>

                </div>

            </div>

            <!-- Square position absolute -->
            <div class="square">
                <i class="fa-solid fa-tag"></i>
            </div>

            <!-- Square position absolute -->
            <div class="square1">
                <span class="color_green small">$</span>
                <span class="color_green number">39</span>
                <p>On Sale</p>
            </div>

        </div>
    </div>
</template>



<style scoped>
.bg_img {
    width: 100%;
    height: 570px;
    object-fit: cover;
        
    
}

.container {
    /* background-image: url(../assets/img/home1/home1_slide_three_bg_2.jpg); */
    position: relative;
}

.new_arrivals {
    height: 430px;
    padding: 0 0 5rem;
    text-align: center;
    margin: 6rem 0 0;
    position: absolute;
    top: -12px;
    left: auto;

    & h1 {
        color: var(--bg-primary);
        font-size: 50px;
        margin: 0 0 0.5rem
    }

    & h5 {
        color: var(--bg-gray-light);
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

.color {
    background-color: #f5f5f523;
}

.square {
    position: absolute;
    top: -20px;
    right: 15px;
    border-radius: 7px;
    background-color: var(--bg-primary);
    padding: 1rem;
    box-shadow: 1px 2px 3px 1px;
}

.square1 {
    position: absolute;
    top: 40px;
    right: 15px;
    border-radius: 7px;
    background-color: var(--bg-primary);
    padding: 0.7rem;
    box-shadow: 1px 2px 3px 1px;

    & .small {
        font-size: 9px;
        position: relative;
        bottom: 8px;
    }

    & .number {
        font-size: 20px;
    }

    & p {
        font-size: 8px;
    }

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

.m_05 {
    margin: 0 0.5rem;
}


/* Color */

.color_green {
    color: #46e230;
}
</style>