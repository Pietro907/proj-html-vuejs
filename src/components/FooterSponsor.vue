

<script>
export default {
    name: 'FooterSponsor',
    data() {
        return {
            menuSponsor: [
                {
                    title: 'brands logo',
                },
            ],
            brands: [
                {
                    id: 1,
                    logo: 'src/assets/img/logo/b_logotype_6.png',
                },
                {
                    id: 2,
                    logo: 'src/assets/img/logo/b_logotype_7.png',
                },
                {
                    id: 3,
                    logo: 'src/assets/img/logo/b_logotype_1.png',
                },
                {
                    id: 4,
                    logo: 'src/assets/img/logo/b_logotype_2.png',
                },
                {
                    id: 5,
                    logo: 'src/assets/img/logo/b_logotype_3.png',
                },
            ],
            
            bgSponsorColor: 'var(--bg-white-smoke)',
        }
    }
}
</script>

<template>
    <div class="container" :value="bgSponsorColor" :style="{ backgroundColor: bgSponsorColor }" >
        <div class="row r_60">

            <h4>{{ menuSponsor[0].title.toUpperCase() }}</h4>

            <div class="col title d_flex jst_btw">

                <div v-for="(menu, id) in brands" class="card">
                    <img :key="id" :src="menu.logo" alt="">
                </div>

                <!-- <div class="card">
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
 -->
            </div>
        </div>
    </div>
</template>


<style scoped>
.container {
   /*  background-color: var(--bg-white-smoke); */
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