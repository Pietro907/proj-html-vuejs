<script>
export default {
    name: 'MainTestimonial',

}
</script>


<template>
    <div class="container">
        <div class="row">
            <div class="col d_flex jst_center align_center">

                <div class="card new_arrivals d_flex f_column jst_center">

                    <div class="card testimonila_avatar">
                        <img src="../assets/img/man_testimonial.png" alt="">
                    </div>

                    <p>Curabitur non tristique tortor. Verstibulum akiquet suscipit ipsum in volutpat. Donec vel lacinia
                        sem, vitae semper nulla. In hac habitasse platea dictumst. Marius consectetur est et nibh sadip
                        hendererit bidendum.</p>
                    <p><b>Darìo Pineda</b>, Theme Fusion</p>

                    <div class="btn">

                        <button class="color m_05" type="button"></button>
                        <button class="color m_05" type="button"></button>

                    </div>
                </div>

            </div>

        </div>
    </div>

</template>



<style scoped>
.container {
    background-image: url(../assets/img/home1/testimonials_home_1_bg.jpg);
    height: 400px;
    margin: 7rem 0;
    background-size: cover;
    background-position: right;
    background-repeat: no-repeat;
    position: relative;
}

.new_arrivals {
    width: 40%;
    height: 430px;
    padding: 0 0 5rem;
    text-align: center;
    margin: 2rem 0 0;

    & p {
        color: var(--bg-gray-light);
        font-size: 15px;
        margin: 0 0 1.5rem
    }
}

.btn>button {
    font-size: 9px;
    padding: 0.2rem;
    border-radius: 20px;
    border-color: var(--bg-primary);
    color: var(--bg-primary);
}

.btn>button:first-child {
    background-color: var(--bg-primary);
}

.color {
    background-color: #f5f5f523;
}

.testimonila_avatar {
    margin: 0 0 2rem;
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


/* Color */</style>