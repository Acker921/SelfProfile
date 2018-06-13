<template>
    <div class="nav">
        <div class="navbar">
            <div class="logo">
                <img src="../assets/logo.png" alt="" height="30px">
            </div>
            <ul class="navlist">
                <li>主页</li>
                <li>博客</li>
                <li>关于</li>
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
        max-width: 70%;
        width: 70vw;
        margin: 0 auto;
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
</style>
