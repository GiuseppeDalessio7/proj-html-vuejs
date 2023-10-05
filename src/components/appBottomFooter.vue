<script>
import props from '../props';
import appDynamicFooter from './appDynamicFooter.vue';

export default {
    name: 'appBottomFooter',
    components: {
        appDynamicFooter
    },

    data() {
        return {
            props
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
    <appDynamicFooter></appDynamicFooter>
</template>

<style lang="scss" scoped>
a {
    text-decoration: none;
    color: #acabac;
}

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
