<template>
    <div class="main">
        <article class="item">
            <div class="inneritem1">
                <div class="main-item">
                    <h1 class="item-text1">
                        <strong>Team</strong> Nextdev
                    </h1>
                    <div class="item-desc">
                        <div class="item-tags1">
                            Devlopers Team / Profile
                        </div>
                        <div class="item-btns">
                            <a class="item-btn1" href="http://nextdev.cn" target="_blank">Launch Site</a>
                        </div>
                    </div>
                </div>
                <img src="../assets/nextdev1.png" alt="" class="image1">
            </div>
        </article>
        <article class="item">
            <div class="inneritem2">
                <div class="main-item">
                    <h1 class="item-text2">
                        <strong>Program</strong> Encodeo
                    </h1>
                    <div class="item-desc">
                        <div class="item-tags2">
                            Web App / Android APP
                        </div>
                        <div class="item-btns">
                            <a class="item-btn2" href="" target="_blank">Coming soon</a>
                        </div>
                    </div>
                </div>
                <img src="../assets/encodeo.png" alt="" class="image2">
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
    .inneritem1 {
        background: #2f374a;
        height: 50em;
        margin: 1rem 1rem 0;
        border-radius: .6rem;
        position: relative;
        overflow: hidden;
    }
    .inneritem2 {
        background: rgb(245, 245, 245);
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
    .item-text1 {
        color: #00c1d3;
        font-size: 2.25rem;
        font-weight: 100;
        z-index: 999;
        padding: 0 .5em 0 0;
        line-height: 1.2;
        text-align: left;
        position: relative;
    }
    .item-text2 {
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
    .image1 {
        position: absolute;
        top: 10%;
        right: 5%;
        width: 50%;
    }
    .image2 {
        position: absolute;
        bottom: -6%;
        right: -3%;
        width: 65%
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
    .item-tags1 {
        color: #fff;
    }
    .item-btn1 {
        color: #ccc;
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
    .item-tags2 {
        color: #9e9d99;
    }
    .item-btn2 {
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
