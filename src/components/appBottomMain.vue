<script>
export default {
    name: 'appBottomMain',

    data() {
        return {

        }
    },




}
</script>

<template>
    <div class="d-flex">
        <div>
            <img class="left_img" src="../assets/img/why.png" alt="">
        </div>
        <div class="p-5">
            <img src="../assets/img/dog-icon.png" alt="">
            <small class="mx-2 small">Choose Us</small>
            <h2 class="my-1">Why Choose Us?</h2>
            <div class=" right ">
                <div class="right d-flex left_margin1">
                    <img src="../assets/img/w-3.png" alt="">
                    <div class=" p-3 my_width1 ">
                        <h5 class=" my-1">Safety first</h5>
                        <p class="">it is a long established fact that a reader will be distructed by the readable content
                            of a page
                            when
                            looking at its layout.</p>
                    </div>
                </div>

                <div class="right d-flex left_margin2">
                    <img src="../assets/img/w-2.png" alt="">
                    <div class=" p-3 w-50 my-2">
                        <h5 class=" ">Safety first</h5>
                        <p>it is a long established fact that a reader
                            will be distructed by the readable content of
                            a page
                            when
                            looking at its layout.</p>
                    </div>
                </div>
                <div class="right d-flex left_margin3">
                    <img src="../assets/img/w-1.png" alt="">
                    <div class=" p-3 my_width my-1">
                        <h5 class=" ">Safety first</h5>
                        <p>it is a long established fact that a reader
                            will be distructed by the readable content of
                            a page
                            when
                            looking at its layout.</p>
                    </div>
                </div>

            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
.small {
    font-weight: 500;
    color: #93887b;
}

.left_img {
    width: 650px;
    margin-bottom: 3rem;
}

.right>img {
    width: 180px;
    padding: 1rem;
}

.left_margin1 {
    margin-left: -1rem;
}

.left_margin2 {
    margin-left: 165px;
    margin-top: -2.5rem;
}

.left_margin3 {
    margin-left: 345px;
    margin-top: -2.5rem;
}

.my_width {
    width: 300px;
}

.my_width1 {
    width: 700px;
}
</style>
