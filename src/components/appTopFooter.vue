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
        <div class="my_box" style="margin-left: 12rem;">
            <img src="../assets/img/dog-icon.png" alt="">
            <small class="brown_font"> Review and rating</small>
            <h3 class="my-3">Over 8000 Customers With 5-Star Review</h3>
            <p class="my_font">
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
        <div class="my_box p-3" style="background-color: #f4f5f5;margin-left: -5rem;">
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <h5 class="" style="margin-top: 1rem;">Great Place</h5>
            <p class="my_font_p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro eveniet mollitia eum
                officiis
                laboriosam
                consequuntur fugit recusandae at hic nulla quis.</p>
            <img id="designer" src="../assets/img/t1.png" alt="">
            <div class="d-flex flex-column my_direction">
                <h5 class="myfont">Tobias May</h5>
                <small class="" style="font-size: 11px;">UI/UX Designer</small>
            </div>

        </div>
        <div class="my_box p-3" style="background-color: #f4f5f5;margin-left: -5rem;">
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <i class="fa-solid fa-star" style="color: #fbd608;"></i>
            <h5 class="" style="margin-top: 1rem;">Great Place</h5>
            <p class="my_font_p">Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro eveniet mollitia eum
                officiis
                laboriosam
                consequuntur fugit recusandae at hic nulla quis.</p>
            <img id="designer" src="../assets/img/t1.png" alt="">
            <div class="d-flex flex-column my_direction">
                <h5 class="myfont">Tobias May</h5>
                <small class="" style="font-size: 11px;">UI/UX Designer</small>
            </div>
        </div>
    </div>
    <div class="container">
        <div class=" nexteprev text-end">
            <img src="../assets/img/left-arrow.png" alt="">
            <img src="../assets/img/next.png" alt="">
        </div>
    </div>
</template>


<style lang="scss" scoped>
.nexteprev {
    width: 1182px;
}

.nexteprev>img {
    width: 45px;
    aspect-ratio: 1/1;
    background-color: #ce7c2a;
    margin: 10px;
    padding: 10px;

}

.brown_font {
    font-weight: 500;
    color: #93887b;
}

.myfont {
    font-size: 15px;
    font-family: 'DM Sans', sans-serif;
    font-family: 'Gabarito', cursive;
    font-weight: 500;
}

.my_direction {
    margin-left: 60px;
    margin-top: -42px;
}

#designer {
    width: 45px;
    aspect-ratio: 1/1;
    border-radius: 25px;
}

.my_box {
    width: 300px;
    height: 250px;
    margin: 0 auto;
}

.my_box>img {
    width: 30px;
}

.my_font {
    font-size: 12px;
    font-weight: 400;
}

.my_font_p {
    font-size: 14px;
    font-weight: 400;
}
</style>