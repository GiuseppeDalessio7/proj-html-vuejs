<script>
export default {
    name: 'appTopFooter',

    data() {
        return {

        }
    },




}
</script>

<template>
    <div class="container d-flex p-3">
        <div class="my_box">
            <img src="../assets/img/dog-icon.png" alt="">
            <small> Review and rating</small>
            <h3 class="my-3">Over 8000 Customers With 5-Star Review</h3>
            <p>
                it is a long established fact that a reader will be distructed by the readable content
                of a page
                when
                looking at its layout.</p>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>

            <img src="../assets/img/" alt="">
        </div>
        <div class="my_box">
        </div>
        <div class="my_box">
        </div>
    </div>
</template>


<style lang="scss" scoped>
.my_box {
    width: 300px;
    height: 250px;
    margin: 0 auto;
}

.my_box>img {
    width: 30px;
}
</style>