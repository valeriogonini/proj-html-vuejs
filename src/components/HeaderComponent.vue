<template>
    <header>
        <div class="container-lg">
            <div class="row header-1">
                <div class="lista-1">
                    <a href=""><img class="img-1" src="/public/img/HelloIMG1669149314369.png" alt=""></a>
                </div>
                <ul class="lista-1">
                    <li v-for="(navs, i) in nav"><a href="">{{ navs }}</a></li>
                    <li>
                        <button class="button-inizia"><a href="">Donate</a></button>
                    </li>
                </ul>
            </div>
        </div>
        <section class="section-header">
            <h1 class="title-header">MAKE A DIFFERENCE</h1>
            <P>As long a poverty, injustice & inequality persist, none of us can truly rest</P>
            <div class="button-header">
                <button class="button-mission"><a href="">OUR MISSION</a> </button>
                <button class="button-donate"><a href="">DONATE NOW</a></button>
            </div>

        </section>
    </header>

</template>

<script>
export default {
    data() {
        return {
            nav: {
                home: 'Home',
                mission: 'Mission',
                causes: 'Causes',
                jornal: 'jornaul'
            }


        }
    }
}
</script>

<style lang="scss" scoped>
@use '../style/partials/header';
</style>