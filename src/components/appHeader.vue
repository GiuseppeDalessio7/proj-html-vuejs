<script>
export default {
    name: 'appheader',

    data() {
        return {

        }
    },




}
</script>

<template>
    <div class="my_color">
        <div class="container d-flex justify-content-between p-3 ">
            <div class="align-items-center">
                <i class="fa-solid fa-envelope mx-2" style="color: #ce7c2a;"></i>
                <small class="text-white my_text ">info@example.com</small>
                <i class="fa-solid fa-phone mx-3" style="color: #ce7c2a;"></i>
                <small class="text-white my_text my_margin">+1(817)901 3377</small>
            </div>

            <div class="">
                <i class="fa-brands fa-square-facebook mx-1 my_icon" style="color: #005eff"></i>
                <i class="fa-brands fa-square-pinterest mx-1 my_icon" style="color: #c92626;
                "></i>
                <i class="fa-brands fa-square-twitter mx-1 my_icon" style="color: #00a8f0;
                "></i>
                <i class="fa-brands fa-linkedin mx-1 my_icon" style="color: #2062d5;
                "></i>
                <i class="fa-brands fa-square-instagram mx-1 my_icon" style="color: #cd1392;
                "></i>
            </div>
        </div>
    </div>
    <div>
        <div class="container p-3 d-flex justify-content-between align-items-center">
            <div class="justify-content-between">
                <img id="logo" src="../assets/img/logo.png" alt="">
            </div>
            <div class="">
                <a class="text-decoration-none mx-2 text-secondary my_text mybold " href="">Home</a>
                <a class="text-decoration-none mx-2 text-secondary my_text mybold" href="">About</a>
                <a class="text-decoration-none mx-2 text-secondary my_text mybold" href="">Services</a>
                <a class="text-decoration-none mx-2 text-secondary my_text mybold" href="">Training</a>
                <a class="text-decoration-none mx-2 text-secondary my_text mybold" href="">Blogs</a>
                <a class="text-decoration-none mx-2 text-secondary text-white my_button mybold " href="">Get In Toch!</a>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.my_color {
    background-color: #7f7045;
}

.my_margin {
    margin-left: -10px;
}

.my_text {
    font-weight: 400;
}

.mybold {
    font-weight: 500;
    font-size: small;
}

.my_button {
    width: 30px;
    height: 40px;
    padding: 8px;
    padding-left: 10px;
    padding-right: 10px;
    border-radius: 25px;
    background-color: #ce7c2a;
}

.my_icon {
    width: 12.2px;
    height: 14px;
    background-color: white;
    box-shadow: #7f7045 0px 8px 24px;
    border-radius: 10px;
}

#logo {
    width: 150px;
    height: 100%;
}
</style>
