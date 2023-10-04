<script>
export default {
    name: 'appTopMain',

    data() {
        return {

        }
    },

}
</script>








<template>
    <div class="my_backg">
        <div class="container justify-content-between d-flex  position-relative">
            <div>
                <img class="myimg" src="../assets/img/about.png" alt="">
            </div>
            <div class=" myposition">
                <img class="myicon my-2 margin_l " src="../assets/img/dog-icon.png" alt="">
                <small class="mx-2 my_color">About us</small>
                <h3>Welcome DogMilo Pets</h3>
                <p class="margin_t">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Mollitia non atque sit
                    saepe?
                    Perspiciatis
                    asperiores eveniet totam quidem quisquam nostrum quas deserunt, illum voluptates atque cum quos aliquid
                    accusantium. Ullam!</p>
                <p class="margin_t">Lorem ipsum dolor sit amet consectetur adipisicing elit. Impedit, earum corrupti at
                    facere rerum
                    adipisci
                    quia, natus dolorum molestias fugit inventore. Perspiciatis saepe incidunt deleniti, suscipit quam
                    repellendus culpa tempora.</p>
            </div>
        </div>
    </div>
    <div class="my_backcolor" style=" background-color: #f4f4f5;">
        <div class="container">
            <div class="text-center my_h">
                <p class="my_color padding ">Service</p>
                <h5 class="my_h text-center">DogMilo Pet Care Service
                    For Your Best Friends.</h5>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.my_h {
    width: 250px;
    margin: auto;
    // margin-left: 425px;
}

.my_backg {
    background-image: url(../assets/img/dog-logo.png);
    background-repeat: no-repeat;
    background-position: right top 40px;
    background-size: 150px;
}


.my_backcolor {
    width: 100%;
    height: 400px;
    background: url(../assets/img/dog-logo.png) right top 40px no-repeat, url(../assets/img/dog-left.png) left top 35px no-repeat;
    background-size: 150px, 100px;
}

.myimg {
    width: 320px;
    padding-top: 4rem;
    padding-bottom: 4rem;
    margin-left: -10px;
}

.myicon {
    width: 35px;
    height: 35px;
}

.my_color {
    color: #93887b;
    font-size: 12px;
    font-weight: 500;
}

.myposition {
    width: 400px;
    height: 200px;
    position: absolute;
    top: 100px;
    right: 300px;
}

.margin_t {
    margin-top: 1rem;
    font-size: 13px;
    font-weight: 500;
}

.margin_l {
    margin-left: -4px;
}

.padding {
    padding-top: 2rem;
    padding-bottom: 5px;
}
</style>
