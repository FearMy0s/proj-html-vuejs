<template>
  <div class="Header">
    <div class="container">
        <div class="logo">
        <img src="../../assets/img/takeout-logo.png" alt="">
            <div class="navbar">
                <a href="" class="fakehover">Home <i class="fa-solid fa-chevron-down"></i></a>
                <a href="">OrderOnline</a>
                <a href="">About</a>
                <a href="">News</a>
                <a href="">Contact Us</a>
            </div>
        </div>
        <div class="Hero">
            <h2>Hungry?</h2>
            <h1 class="attraction">GreatFood </h1>
            <h1>Delivered</h1>
            <button class="pressme">WIEW OUR MENU <i class="arrow-left fa-solid fa-circle-arrow-right"></i></button>
        </div>
        <div class="container-md">
            <div class="Benefit">
            <h5><i class="font-a fa-solid fa-clock"></i>24/7 DELIVERY</h5>
            <h5><i class="font-a fa-solid fa-burger"></i>OVER 100 DISHES</h5>
            <h5><i class="font-a fa-solid fa-mobile"></i>IN APP ORDERING</h5>
            <h5><i class="font-a fa-solid fa-car"></i>FAST DELIVERY</h5>
            </div>
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
.arrow-left{
    margin-bottom: 5px;
    margin-left: 15px;
}
.logo{
    display: flex;
    justify-content: space-between;

    .navbar{
        margin-top: 50px;
        gap: 50px;
        color: white;
    }
   a{
    font-size: 20px;
    text-decoration: none;
    color: white;
   }
   a:hover{
  color:gold;
    }

}
.Hero{
    color: white;
    margin-top: 150px;
}
h1{
    
    font-size: 100px;
}
.Benefit{
    background-color: white;
    display: flex;
    justify-content: space-around;
   h5{
    margin-top: 50px;
   }
   .font-a{
    margin-bottom: 5px;
    margin-right: 10px;
   }
}


</style>