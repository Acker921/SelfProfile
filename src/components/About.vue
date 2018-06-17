<template>
    <div class="about" id="about">
        <article class="about1">
            <h1 class="item-text">
                <strong>About</strong> me
            </h1>
            <div class="item-desc">
                <div>我喜欢创造</div>
                <div>但我更喜欢用代码来实现美的艺术</div>
            </div>
        </article>
        <article class="about2">
            <h1 class="item-text">
                <strong>Contact</strong> Me
            </h1>
            <div class="item-desc">
                <div>0ingxiao@gmail.com · E-mail</div>
                <div>741605807 ·  QQ</div>
            </div>
        </article>
        <hr class="segment">
        <h1 class="copyright">© 2018 Acker. All rights reserved.</h1>
    </div>
</template>

<script>
export default {
    name: 'About'
}
</script>

<style scoped>
    .about {
        width: 70vw;
        max-width: 70%;
        margin: 0 auto;
        clear: both;
    }
    .about1 {
        padding: 10rem 0 1rem;
        clear: both;
        position: relative;
        margin: 0 auto;
    }
    .about2 {
        padding: 3rem 0 3rem;
        clear: both;
        position: relative;
        margin: 0 auto;
    }
    .item-text {
        color: #333;
        float: left;
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
    .item-desc {
        text-align: left;
        font-size: .875rem;
        font-weight: 400;
        line-height: 1.63;
        display: block;
        width: 62%;
        float: right;
        padding: 0;
        margin: .1rem 0 0;
        color: #333;
    }
    .item-desc div {
        margin: 0 0 0.5rem;
        color: #333;
        font-size: 1.25rem;
        font-weight: 100;
        z-index: 999;
        padding: 0 .5em 0 0;
        line-height: 1.2;
        text-align: left;
        position: relative;
    }
    .segment {
        margin: 3rem auto 1rem;
    }
    .copyright {
        font-weight: 100;
        margin-bottom: 2rem;
    }
</style>
