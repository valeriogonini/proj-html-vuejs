<template>
    <section class="section-ft">
        <div class="img-footer">
            <img src="/public/img/HelloIMG1669149314987.png" alt="">
        </div>
        <p class="p-footer">Copyright 2012 - 2022 | Avada Theme by <span class="color-yl">ThemeFusion</span> | All
            Rights Reserved |
            Powered by
            <span class="color-yl">WordPress</span>
        </p>
        <ul class="list-footer">
            <li v-for="(socials, i) in social"><a href="">{{ socials }}</a></li>
        </ul>
    </section>


</template>

<script>
export default {
    data() {
        return {
            social: {
                facebook: 'F',
                instagram: 'I',
                twitter: 'X',
                youtube: 'YT'
            }


        }
    }
}
</script>

<style lang="scss" scoped>
@use '../style/partials/footer';
</style>