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
    <div class="orangeb d-flex">
        <img src="../assets/img/news.png" alt="">

        <div class="input-group input mb-3">
            <span id="spantext" class="marginspan text-white spantext">Subscribe to Our Newsletter</span>
            <input type="text" class="form-control  margin " placeholder="Your Email Here" aria-label="Recipient's username"
                aria-describedby="basic-addon2">
            <span class="input-group-text widthspan margin text-uppercase" id="addon-wrapping">@</span>
        </div>
    </div>
    <div class="my_bg">
        <div class="container position-relative ">
            <div class="container mycontainer d-flex">
                <ul class=""> <span>Get in Touch</span>
                    <li>Have a question for us?
                        we'll answer your problem here
                    </li>
                    <li class="li_icon"><i class="fa-brands fa-square-facebook fa-xl mx-1 my-1 my_icon"
                            style="color: #005eff"></i>
                        <i class="fa-brands fa-square-pinterest fa-xl mx-1 my_icon" style="color: #c92626;
"></i>
                        <i class="fa-brands fa-square-twitter fa-xl mx-1 my_icon" style="color: #00a8f0;
"></i>
                        <i class="fa-brands fa-linkedin fa-xl mx-1 my_icon" style="color: #2062d5;
"></i>
                        <i class="fa-brands fa-square-instagram fa-xl mx-1 my_icon" style="color: #cd1392;
"></i>
                    </li>
                </ul>
                <ul class=""> <span>Support</span>
                    <li>Contact Us</li>
                    <li>Online Chat</li>
                    <li>Whatsapp</li>
                    <li>Telegram</li>
                    <li>Snapchat</li>
                </ul>
                <ul class="li_render"> <span>About</span>
                    <li>About Us</li>
                    <li>Blog</li>
                    <li>Career</li>
                    <li>Job</li>
                    <li>In press</li>
                </ul>
                <ul class="li_render"> <span>Faq</span>
                    <li>Account</li>
                    <li>Order</li>
                    <li>Delivery</li>
                    <li>Payment</li>
                    <li>Return</li>
                </ul>
                <ul class="li_render"> <span>Contact Me</span>
                    <li> <i class="fa-solid fa-location-arrow i_render" style="color: #ce7c2a;"></i>4500 Mercantile plaza,
                        suite 300,
                        fort worth,TX,76137,USA</li>
                    <li> <i class="fa-solid fa-phone i_render " style="color: #ce7c2a;"></i>+1(817)901 3373</li>
                    <li> <i class="fa-solid fa-envelope i_render " style="color: #ce7c2a;"></i>info@example.com</li>
                </ul>
            </div>
        </div>
        <div class="my_cont text-center">
            <p class="text-white ">Copyright 2022 by AttDogMilo.com</p>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.my_cont {
    width: 100%;
    height: 70px;
    background-color: black;
    border-top: 0.5px solid #acabac;
    padding: 1.5rem;

}

.i_render {
    margin-right: 10px;
}

.li_render {
    margin-left: -80px;
}

.li_icon {
    margin-top: 1rem;
    margin-left: -4px;
}

.my_icon {
    border-radius: 10px;
}

ul>span {
    color: #ce7c2a;
    font-weight: 500;
    font-size: 17px;
    font-family: 'DM Sans', sans-serif;
    font-family: 'Gabarito', cursive;
}

ul {
    list-style: none;
    width: 250px;


}

li {
    color: #acabac;
    margin-top: 0.5rem;
}

.mycontainer {
    padding-top: 8rem;
    margin: auto;
    margin-left: 10rem;
    font-size: 14px;
}



#spantext {
    font-size: 20px;
    top: 35px;
    font-weight: 700;
    position: absolute;
}

.widthspan {
    width: 45px;
    height: 50px;
    aspect-ratio: 1/1;
    background-color: #ce7c2a;
    color: white;
    font-size: 25px;
    margin-right: 1rem;


}


// .marginspan {
// margin-top: 2.5rem;
// 
// }

.margin {
    margin-top: 4.5rem;


}

.container {
    height: 100%;
}

.input {
    width: 500px;
    height: 50px;
    margin-left: 7rem;
}

.my_bg {
    width: 100%;
    height: 350px;
    background-color: black;
    margin-top: 9.5rem;

}

.orangeb {
    width: 800px;
    height: 150px;
    margin-top: 5rem;
    position: absolute;
    margin-left: 34rem;
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
