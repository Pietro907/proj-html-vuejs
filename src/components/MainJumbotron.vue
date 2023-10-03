
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
        <div class="col d_flex jst_center align_center">
            
            <div class="card">
                <h1>Brand New Arrivals</h1>
                <h5>NEW COLLECTION FORM NEW YORK</h5>

                <div class="btn">

                    <button type="button">VIEW ALL</button>
                    <button type="button">LOOKBOOK</button>

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