

<script>
export default {
    name: 'FooterAvadaShop',
}
</script>

<template>
    <div class="container">
        <div class="row r_60 d_flex">

            <div class="col logo_col d_flex f_column jst_start">

                <div class="card logo_shop">
                    <img class="logo_shop" src="../assets/img/classic_shop/classic_shop_logo_footer.png" alt="">
                </div>

                <div class="card address">

                    <p class="p_y05">12345 North Maon Street,</p><br>
                    <p>New York, Ny 555555</p><br>
                    <p>Phone:1.800.555.6789</p><br>
                    <p>Email; info@company.com</p><br>
                    <p>Web: Theme-fusion.com</p><br>

                </div>

                <div class="card brands_logo">

                    <i class="fa-brands fa-facebook-f"></i>
                    <i class="fa-solid fa-brands fa-twitter"></i>
                    <i class="fa-solid fa-brands fa-instagram"></i>
                    <i class="fa-solid fa-brands fa-youtube"></i>

                </div>

            </div>

            <div class="col logo_col_1">

                <div class="card title">
                    <h4>Top Rated Products</h4>
                </div>

                <div class="card products">

                    <div class="info d_flex ">

                        <div class="info_cost d_flex f_column">

                            <h5>Leather Gloves</h5>
                            <i class="fa-solid fa-star"></i>
                            <p class="style_line"><b>$45</b></p>

                        </div>

                        <div class="logo_img">
                            <img src="../assets/img/leather_gloves/leather_gloves-120x156.jpg" alt="">
                        </div>

                    </div>


                    <div class="line_gray"></div>

                </div>

                <div class="card products">

                    <div class="info d_flex ">

                        <div class="info_cost d_flex f_column">

                            <h5>Black Leather Jacket</h5>
                            <i class="fa-solid fa-star"></i>

                            <div class="cost d_flex align_center jst_start">
                                <p class="style_line_through"><b>$235</b></p>
                                <span class="style_line_underline"><b>$235</b></span>
                            </div>

                        </div>

                        <div class="logo_img">
                            <img src="../assets/img/black_elegant_man/black_elegant_leather_jacket-120x156.jpg" alt="">
                        </div>

                    </div>

                    <div class="line_gray"></div>

                </div>

                <div class="card products d_flex f_column">
                    <div class="info d_flex">

                        <div class="info_cost">

                            <h5>Spring Printed Dress</h5>
                            <i class="fa-solid fa-star"></i>
                            <i class="fa-solid fa-star"></i>
                            <p class="style_line"><b>$47</b></p>

                        </div>

                        <div class="logo_img">
                            <img src="../assets/img/collections/spring/spring_printed_dress-120x156.jpg" alt="">
                        </div>

                    </div>


                    <div class="line_gray"></div>

                </div>

            </div>

            <div class="col logo_col_1">
    
                <div class="card title">
                    <h4>Recent Posts</h4>
                </div>
    
                <div class="card address">
    
                    <div class="top"><i class="fa-solid fa-angle-right"></i>
                        <span>Aenean lobortis sapien enim viverra</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                    <div class="bot">
                        <i class="fa-solid fa-angle-right"></i>
                        <span>Duis ac massa semper maximus</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                </div>
    
                <div class="card address">
    
                    <div class="top"><i class="fa-solid fa-angle-right"></i>
                        <span>Aenean lobortis sapien enim viverra</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                    <div class="bot">
                        <i class="fa-solid fa-angle-right"></i>
                        <span>Duis ac massa semper maximus</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                </div>
    
                <div class="card address">
    
                    <div class="top"><i class="fa-solid fa-angle-right"></i>
                        <span>Aenean lobortis sapien enim viverra</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                    <div class="bot">
                        <i class="fa-solid fa-angle-right"></i>
                        <span>Duis ac massa semper maximus</span>
                    </div>
    
                    <div class="line_gray"></div>
    
                </div>
    
            </div>
    
            <div class="col logo_col_1">
    
                <div class="card title all_tags d_flex f_column">
                    <h4>Tags</h4>
    
                    <div class="tags d_flex jst_center  f_wrap">
    
                        <a href="">Black</a>
                        <a href="">boots</a>
                        <a href="">Brown</a>
                        <a href="">Casual</a>
                        <a href="">D&G</a>
                        <a href="">Fabric</a>
                        <a href="">flowers</a>
                        <a href="">Grey</a>
                        <a href="">hat</a>
                        <a href="">Hipster</a>
                        <a href="">lines</a>
                        <a href="">multi-purpose</a>
                        <a href="">New York</a>
                        <a href="">Outdoors</a>
                        <a href="">red</a>
                        <a href="">responsive</a>
                        <a href="">summer</a>
                        <a href="">sweater</a>
                        <a href="">Travel</a>
                        <a href="">Warm</a>
                        <a href="">White</a>
                        <a href="">winter</a>
    
                    </div>
    
                </div>
            </div>
        
        </div>

    </div>
</template>

<style scoped>
.container {
    background-color: var(--bg-footer-avada);
    padding: 2rem 0;
}

.r_60 {
    width: 60%;
    margin: 0 auto 5rem;
    padding: 2rem 0;
    
}

.card {
    width: 240px;
}

.logo_shop {
    width: 240px;
}

.logo_img>img {
    width: 90px;
    margin: 0.5rem 0 -0.5rem 4rem;
}

.logo_col {
    padding: 1rem;
    height: 350px;
}

.logo_col_1 {
    padding: 0.4rem;
    height: 350px;
}

.logo_col>.card {
    padding: 1rem 0;
}

p {
    margin: -0.3rem;
}

.address {
    color: var(--bg-gray-light);
    padding: 1rem 0 0;
}

.brands_logo>i {
    padding: 0 0.5rem;
    color: var(--bg-gray-light);
}

.title {
    color: var(--bg-white-smoke);
    font-size: 20px;
}
.info{
    padding: 0 0 0.5rem;
}
.info_cost>h5 {
    padding: 2rem 0 0.5rem;
    color: var(--bg-gray-light);
}

.info_cost>.fa-star {
    color: var(--bg-heaven);
    margin: 0.5rem 0;
}

.info_cost>h5 {
    padding: 1rem 0 0.5rem;
    color: var(--bg-gray-light);
}

.info_cost>p {
    color: var(--bg-white-smoke);
    padding: 1rem 0 0 0.2rem;
}

.cost>p {
    color: var(--bg-white-smoke);
    padding: 1rem 0.5rem 1rem 0;
}

.line_gray {
    background-color: var(--bg-gray-light);
    height: 0.5px;
    margin: 1rem 0 0;
}

.tags>a {
    text-decoration: none;
    color: var(--bg-gray-light);
    border: 0.5px solid var(--bg-gray-light);
    text-align: center;
    padding: 0.5rem;
    margin: 0.2rem;
    font-size: 18px;
}

.style_line_through {
    text-decoration-line: line-through;
}

.style_line_underline {
    text-decoration-line: underline;
    color: var(--bg-white-smoke);
}

.top {
    font-size: 15px;
    padding: 1rem 0;
}

.bot {
    font-size: 15px;
    padding: 1.5rem 0 0.5rem;
}

.top>i,
.bot>i {
    padding-right: 0.5rem;
}




/* Utilities */
.d_flex {
    display: flex;
}

.f_column {
    flex-direction: column;
}

.f_wrap {
    flex-wrap: wrap;
}

.jst_center {
    justify-content: center;
}

.jst_start {
    justify-content: start;
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