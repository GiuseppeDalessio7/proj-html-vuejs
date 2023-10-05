<script >

export default {
    props: ["name",]
}
</script>

<template>
    <a class="text-decoration-none mx-2 text-secondary my_text mybold " href="">{{ name }}</a>
</template>
  
<style lang="scss" scoped>
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
    color: white;
}
</style>
  