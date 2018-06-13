<template>
    <div class="header">
        <section class="headline">你好，我是 Acker</section>
        <section class="subheadline">我是一名留学生</section>
        <section class="headline">我是一名全栈工程师</section>
        <section class="subheadline">目前干外包行业</section>
        <section class="headline">属于 Nextdev 团队</section>
        <section class="subheadline">一个属于年轻人的团队</section>
    </div>
</template>

<script>
export default {
    name: 'ProfileHeader'
}
</script>

<style scoped>
    .header {
        margin: 0 auto;
        padding: 6rem 0;
    }
    .header section {
        width:70vw;
        max-width: 70%;
        margin: 0 auto;
    }
    .headline {
        font-size: 3rem;
        display: block;
        color: #444;
        text-align: left;
        padding-top: 1rem
    }
    .subheadline {
        font-size: 1.25rem;
        color: #ccc;
        font-weight: 300;
        line-height: 1.3;
        display: block;
        padding: 0.5em 0 1rem;
        text-align: left;
    }
</style>
