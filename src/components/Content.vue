<template>
    <div class="main">
        <article class="item">
            <div class="inneritem">
                <div class="main-item">
                    <h1 class="item-text">
                        <strong>Podcast</strong> RSS Editor
                    </h1>
                    <div class="item-desc">
                        <div class="item-tags">
                            Web App Design / Development
                        </div>
                        <div class="item-btns">
                            <a class="item-btn" href="" target="_blank">More details on Behance</a>
                        </div>
                    </div>
                </div>
                <img src="../assets/Dev.jpg" alt="" class="image">
            </div>
        </article>
    </div>
</template>

<script>
export default {
    name: 'Content'
}
</script>

<style scoped>
    .main {
        max-width: 160em;
        margin: 0 auto;
    }
    .item {
        clear: both;
        position: relative;
        margin: 0 auto;
    }
    .inneritem {
        background: rgb(208, 211, 218);
        height: 50em;
        margin: 1rem 1rem 0;
        border-radius: .6rem;
        position: relative;
        overflow: hidden;
    }
    .main-item {
        padding-top: 12rem;
        margin: 0 auto;
        max-width: 70%;
        width: 70vw;
    }
    .item-text {
        font-size: 2.25rem;
        font-weight: 100;
        z-index: 999;
        padding: 0 .5em 0 0;
        line-height: 1.2;
        text-align: left;
        position: relative;
    }
    .item-text strong {
        font-weight: 700;
        font-style: normal;
    }
    .image {
        position: absolute;
        top: 0;
        right: 0;
        height: 100%;
    }
    .item-desc {
        font-size: .8rem;
        text-align: left;
        padding: 0;
        margin: 3em 0 0;
        line-height: 1.35;
        position: relative;
        font-weight: 400;
    }
    .item-tags {
        color: #9e9d99;
    }
    .item-btn {
        color: #9e9d99;
        display: inline-block;
        border-radius: 2em;
        padding: .3em .7em .5em .5em;
        background: 0 0;
        font-size: .8rem;
        cursor: pointer;
        font-weight: 400;
        text-decoration: none;
        margin: 0 .4em 0 -.5em;
        transition: all .2s cubic-bezier(.4,0,0,1);
        text-decoration: none;
    }
    .item-btn:hover {
        background: #fff;
    }
</style>
