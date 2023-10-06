

<script>
export default {
    name: 'MainFromOurBlog',
}
</script>

<template>
    <!-- Title Page -->
    <div class="featured d_flex jst_center align_center">

        <div class="line_gray"></div>

        <div class="title">

            <h2>From Our Blog</h2>
            <p>The latest Classic Shop news</p>

        </div>

        <div class="line_gray"></div>

    </div>

    <!-- Contenuti Blog -->
    <div class="container">
        <div class="row r_60 d_flex jst_center align_center">

            <!-- Colonna blog -->
            <div class="col">
                <div class="card products">
                    <img src="../assets/img/post/post_img_12-700x441.jpg" alt="">

                    <div class="info_cost">
                        <h5>Aenean lobortis sapien enim viverra</h5>
                        <span class="comments">September 9th, 2015</span>
                        <span class="comments"> | 0 Comments</span>
                        <p>Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla,</p>
                    </div>

                </div>
            </div>

            <!-- Colonna blog -->
            <div class="col">
                <div class="card products">
                    <img src="../assets/img/post/post_img_11-700x441.jpg" alt="">

                    <div class="info_cost">
                        <h5>Aenean lobortis sapien enim viverra</h5>
                        <span class="comments">September 9th, 2015</span>
                        <span class="comments"> | 0 Comments</span>
                        <p>Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla,</p>
                    </div>

                </div>
            </div>
            s
            <!-- Colonna blog -->
            <div class="col">
                <div class="card products">
                    <img src="../assets/img/post/post_img_10-700x441.jpg" alt="">

                    <div class="info_cost">
                        <h5>Aenean lobortis sapien enim viverra</h5>
                        <span class="comments">September 9th, 2015</span>
                        <span class="comments"> | 0 Comments</span>
                        <p>Donec finibus sit amet orci eget ultricies. Praesent posuere ante ut erat fringilla,</p>
                    </div>

                </div>
            </div>

        </div>
    </div>
</template>

<style scoped>
.featured>.title {
    text-align: center;
    margin: 6rem 0 2rem;

    & h2 {
        font-size: 35px;

    }

    & p {
        font-size: 15px;
        color: var(--bg-gray-light);
    }
}

.line_gray {
    background-color: var(--bg-gray-light);
    height: 0.5px;
    width: 20%;
    margin: 2rem 5rem 0;
}

.r_60 {
    width: 60%;
    margin: 0 auto;
    padding: 2rem 0;
}

.products>img {
    width: 300px;
}

.info_cost>h5 {
    padding: 1rem 0 0.2rem;
}

.info_cost>.comments {
    font-size: 12px;
    color: var(--bg-gray-light);
}

p {
    display: inline-block;
    padding: 1rem 0.5rem 0 0;
    font-size: 12px;
}

.col {
    margin: 0 15px 0;
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


/* Color */

.bg_gray_light {
    background-color: var(--bg-white-smoke);
}
</style>