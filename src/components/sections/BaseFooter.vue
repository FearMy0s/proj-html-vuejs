<template>
  <div class="Footer">
    <div class="container">
      <div class="list-section">
        <ul>
        <li><h5>ORDER ONLINE</h5></li>
        <li><a href="">Appetizers</a></li>
        <li><a href="">Burgers</a></li>
        <li><a href="">Pizza</a></li>
        <li><a href="">Fries</a></li>
        <li><a href="">Sides</a></li>
        <li><a href="">Desserts</a></li>
        <li><a href="">Beverages</a></li>
        <li><a href="">Specials</a></li>
        </ul>
        <ul>
          <li><h5>NAVIGATE</h5></li>
          <li><a href="">Home </a></li>
          <li><a href="">Alternate Home</a></li>
          <li><a href="">Menu</a></li>
          <li><a href="">About</a></li>
          <li><a href="">News</a></li>
          <li><a href="">Contact Us</a></li>
          <li><a href="">Cart</a></li>
        </ul>
        <ul>
          <li><h5>INFORMATION</h5></li>
          <li><a href="">My Account</a></li>
          <li><a href="">Terms Of Service</a></li>
          <li><a href="">Privacy Policy</a></li>
          <li><button><img src="../../assets/img/google-play.png" alt=""></button></li>
          <li><button><img src="../../assets/img/apple-store.png" alt=""></button></li>
        </ul>
        <ul>
          <li><h5>OPENING HOURS</h5></li>
          <li><span>Mon - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Tue - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Wed - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Thur - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Fri - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Sat - <span class="Hours">10AM to 11PM</span> </span></li>
          <li><span>Sun - <span class="Hours">11AM to 10PM</span> </span></li>
        </ul>
        <ul class="discount-section">
          <li><h5>VOUCHER</h5></li>
          <li><button><img class="discount-img" src="../../assets/img/discount.png" alt=""></button></li>
          <li class="adjust"><span>Just Use The Code <h4>FRISTORDER</h4><span class="span-model"> At Checkout</span></span></li>
        </ul>
      </div>
    </div>
    <div class="container">
      <div class="Footer-Img">
        <img src="../../assets/img/takeout-logo.png" alt="">
      </div>
           <div class="Footer-Bottom">
          <h1>Stay In The Loop</h1>
          </div>
          <div class="Footer-Bottom">
            <span>Sign up to ricevie up to date news and  offers directly in your inbox:</span>
          </div>
          <div class="Footer-Bottom">
            <input class="Register" type="text" placeholder="you@email">
          </div>
          <div class="Footer-Bottom">
            <button class="Register">SUBSCRIBE</button>
          </div>
           <div class="Footer-Bottom">
            <i class="awesome fa-brands fa-facebook-f"></i>
            <i class="awesome fa-brands fa-twitter"></i>
            <i class="awesome fa-brands fa-instagram"></i>
            <i class="awesome fa-brands fa-linkedin-in"></i>
            <i class="awesome fa-brands fa-youtube"></i>
            <i class="awesome fa-solid fa-envelope"></i>
          </div>
            <div class="Footer-Bottom">
              <span class="Credits">Mirko è Forte</span>
          </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'BaseFooter',

}
</script>

<style lang="scss" scoped>
.Footer{
  background-image: url("../../assets/img/footer-background-scaled.jpg");
  background-size: cover;
  background-repeat: no-repeat;
}
.list-section{
  margin-top: 50px ;
  display: flex;
  gap: 90px;
}
ul{
  list-style:none;
  color: white;
  li{
    margin-top: 30px;
  }
  button{
    background-color: transparent;
    border: none;
    img{
      width: 180px;
      height: 50px;
    }
  }
  .Hours{
    color: gold;
  }
}
a{
  color: white;
  text-decoration: none;
}
a:hover{
  color:gold;
}

.discount-section{
  h5{
    margin-left: 30px;
  }
  .adjust{
    margin-left: 15px;
  }
  h4{
    color: gold;
  }
}
.discount-img{
  margin-right: 20px;
  width: 150px;
  height: 150px;
}
.span-model{
  margin-left: 20px;
}
.Footer-Img{
  margin-top: 70px;
  display: flex;
  justify-content: center;
  margin-bottom: 100px;
}
.Footer-Bottom{
  display: flex;
  justify-content: center;
  color: white;
  h1{
    color: gold;
    font-size: 50px;
  }
  .Register{
    margin-top: 20px;
    width: 600px;
    height: 40px;
    border-radius: 20px;
  }
  button{
    background-color: red;
    color: white;
    border: none;
  }
  .awesome{
    margin-top: 50px;
    margin-left: 50px;
    font-size: 20px;
  }
  .Credits{
    margin-top: 50px;
    color: gold;
    margin-bottom: 200px;
  }
}

</style>