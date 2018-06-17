<template>
    <div class="nav">
        <div class="navbar">
            <div class="logo">
                <img src="../assets/logo.png" alt="" height="32px">
            </div>
            <p class="title"><strong>Acker's</strong> Profile</p>
            <ul class="navlist">
                <li><a href="/">主页</a></li>
                <li><a href="/">博客</a></li>
                <li><a href="#about">关于</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Nav'
}
</script>

<style scoped>
    .nav {
        height: 3rem;
        margin: 0 auto;
        padding: 0 1rem;
        width: 100%;
        max-width: 100vw;
        z-index: 999999;
        position: fixed;
        border: 1px solid #fff;
        border-bottom: 1px solid #ddd;
        background: #fff;
        transition: all .4s cubic-bezier(.4,0,0,1);
    }
    .nav:after, .nav:before {
        width: .6rem;
        height: .6rem;
        display: block;
        content: "";
        position: absolute;
        bottom: -.6rem;
    }
    .nav:before {
        left:1rem
    }
    .nav:after {
        right:1rem;
        transform:rotateY(180deg)
    }
    .logo {
        float: left;
        margin: 0.5rem 0;
        display: inline-block;
    }
    .title {
        display: inline-block;
        padding: 0.75rem 1rem;
        float: left;
        color: #333;
        font-size: 1rem;
        font-weight: 300;
        z-index: 999;
        line-height: 1.2;
    }
    .title strong {
        font-weight: 700;
        font-style: normal;
    }
    .navlist {
        float: right;
        margin: 0;
        width: auto;
    }
    .navlist li {
        display: inline-block;
        padding: 1rem 0.5rem;
        font-size: 0.75rem
    }
    .navlist li a {
        text-decoration: none;
        color: #333
    }
</style>
