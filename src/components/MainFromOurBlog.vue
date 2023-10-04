

<script>
export default {
    name: 'MainFromOurBlog',
}
</script>

<template>
    <div class="featured d_flex jst_center align_center">

        <div class="line_gray"></div>

        <div class="title">

            <h2>From Our Blog</h2>
            <p>The latest Classic Shop news</p>

        </div>

        <div class="line_gray"></div>

    </div>

    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
    <h1>CIAO</h1>
</template>

<style scoped>
.featured>.title {
    text-align: center;
    margin: 6rem 0;

    & h2 {
        font-size: 29px;
        padding: 0.5rem 0;
    }

    & p {
        font-size: 12px;
        color: var(--bg-gray-light);
    }
}

.line_gray {
    background-color: var(--bg-gray-light);
    height: 0.5px;
    width: 20%;
    margin: 0 5rem 0.5rem;
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