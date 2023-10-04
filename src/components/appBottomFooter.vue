<script>
export default {
    name: 'appBottomFooter',

    data() {
        return {

        }
    },




}
</script>

<template>
    <div class="orangeb">
        <img src="../assets/img/news.png" alt="">
    </div>
    <div class="my_bg">
        <div class="container position-relative ">




        </div>
    </div>
</template>

<style lang="scss" scoped>
.container {
    height: 100%;
}

.my_bg {
    width: 100%;
    height: 400px;
    background-color: black;
    margin-top: 9.5rem;

}

.orangeb {
    width: 800px;
    height: 150px;
    margin-top: 5rem;
    position: absolute;
    margin-left: 36rem;
    z-index: 2;
    background-color: #ce7c2a;
    border-radius: 10px;
}

.orangeb>img {
    width: 280px;
    margin-top: -5.8rem;
    margin-left: 2rem;
}
</style>
