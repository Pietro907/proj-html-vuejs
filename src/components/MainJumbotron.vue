
<script>

    export default {
        name: 'MainJumbotron',
        data(){
            return {

            }
        }
    }
</script>


<template>
    
<div class="container">
    <div class="row">
        <div class="col d_flex jst_center">
            
            <div class="card new_arrivals d_flex f_column jst_center">
                <h1>Brand New Arrivals</h1>
                <h5>NEW COLLECTION FORM NEW YORK</h5>

                <div class="btn">

                    <button class="color m_05" type="button">VIEW ALL</button>
                    <button class="color m_05" type="button">LOOKBOOK</button>

                </div>
            </div>

        </div>
    </div>
</div>


</template>



<style scoped>

.container {
    background-image: url(../assets/img/home1/home1_slide_three_bg_2.jpg);
    height: 430px;
    background-size: cover;
    background-position: right;
    background-repeat: no-repeat;
}
.new_arrivals {
    height: 430px;
    padding: 0 0 5rem;
    text-align: center;
    margin: 2rem 0 0;
    & h1{
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
.btn > button {
    font-size: 9px;
    padding: 0.6rem 1.5rem;
    border-radius: 20px;
    border-color: var(--bg-primary);
    color: var(--bg-primary);
} 
.color {
    background-color: #f5f5f523;
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

</style>