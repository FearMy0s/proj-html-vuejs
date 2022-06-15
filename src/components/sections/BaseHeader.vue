<template>
  <div class="Header">
    <div class="container">
        <img src="../../assets/img/takeout-logo.png" alt="">
        <div class="Hero">
            <h2>Hungry?</h2>
            <h1 class="attraction">GreatFood</h1>
            <h1>Delivered</h1>
            <button class="pressme">WIEW OUR MENU <i class="fa-solid fa-arrow-right"></i></button>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'BaseHeader',
}
</script>

<style lang="scss" scoped>
@import '../../assets/style/global.scss';

.Header{
    background-image: url("../../assets/img/burger.jpg");
    background-repeat: no-repeat;
    background-size:cover;
img{
    margin-top: 50px;
}
}
.Hero{
    color: white;
    margin-top: 150px;
}
h1{
    
    font-size: 100px;
}


</style>