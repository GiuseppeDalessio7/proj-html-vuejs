<script>
export default {
    name: 'appJumbotron',

    data() {
        return {

        }
    },




}
</script>

<template>
    <div class="back_img">
        <div class="container position-relative">
            <div class="text-white position my_div ">
                <h2 class="m-0">Welcome to</h2> <span class="mylighter">DogMilo</span> <span class="my_pets">Pets</span>



                <p class="my-3 my_font">Lorem ipsum is simply dummy text of the printing and typesetting industry.</p>
                <div class="my-4">
                    <a class="text-decoration-none  text-secondary 
text-white my_button  " href="">Get Started</a>
                    <img class="my_play" src="../assets/img/play.png" alt="">
                </div>
            </div>
        </div>


    </div>
</template>

<style lang="scss" scoped>
.back_img {
    width: 100%;
    height: 500px;
    background-image: url(../assets/img/b.png);
    background-repeat: no-repeat;
    background-size: 100%;
    background-position: center;
}

.my_pets {
    font-size: 2rem;
    font-weight: 500;
}

.mybold {
    font-weight: bolder;
    font-size: larger;
}


.mylighter {
    font-weight: lighter;
    font-size: 1.9rem;
    font-family: 'DM Sans', sans-serif;
    font-family: 'Gabarito', cursive;
}

.my_font {
    font-size: 13px;
}

.position {
    position: absolute;
    top: 175px;
    left: 10px;
}

.my_div {
    width: 310px;
    height: 150px;
}

.my_button {
    width: 30px;
    height: 40px;
    padding: 10px;
    padding-left: 20px;
    padding-right: 20px;
    border-radius: 25px;
    background-color: #ce7c2a;
    font-weight: 400;
    font-size: larger;
}

.my_play {
    width: 40px;
    aspect-ratio: 1/1;
    border-radius: 10%;
    padding: 6px;
    margin-left: 1rem;
    margin-top: -5px;
    background-color: #71d0f5;
}
</style>
