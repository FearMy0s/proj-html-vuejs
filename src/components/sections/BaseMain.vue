<template>
<div class="Main">
    <div class="container">
        <div class="Dishes">
            <h2>Our Most Popular Dishes</h2>
        </div>
        <div class="Top-Main">
            <div class="fry">
            <img src="../../assets/img/fries.jpg" alt="">
            <h3 class>Skin On Fries</h3>
            <span>$ 3.00 - $ 6.00</span>
            </div>
            <div class="frap">
            <img src="../../assets/img/frappe.jpg" alt="">
            <h3 class>Choco Cookie Frappe</h3>
            <span class>$ 4.99</span>
            </div>
            <div class="donut">
            <img src="../../assets/img/donut-burger.jpg" alt="">
            <h3>The Donut Burger</h3>
            <span>$ 6.99</span>
            </div>
        </div>
        <div class="Top-Main">
            <button class="order">START YOUR ORDER <i class="arrow-left fa-solid fa-circle-arrow-right"></i></button>
        </div>
    </div>
    <div class="Wave">
    </div>
        <div class="container">
            <div class="Mid-Main">
                <h2>Menu Categories</h2> 
                <button class="order orderfix">WIEW THE FULL MENU <i class="arrow-left fa-solid fa-circle-arrow-right"></i> </button>
            </div>
                <div class="Mid-Main-Photo">
                    <div class="Menu-Categiories-Container1 Menu-Categiories-Container"><h3>APPETIZERS</h3></div>
                    <div class="Menu-Categiories-Container2 Menu-Categiories-Container"><h3>BURGERS</h3></div>
                    <div class="Menu-Categiories-Container3 Menu-Categiories-Container"><h3>PIZZAS</h3></div>
                    <div class="Menu-Categiories-Container4 Menu-Categiories-Container"><h3>FRIES</h3></div>
                    <div class="Menu-Categiories-Container5 Menu-Categiories-Container"><h3>SIDES</h3></div>
                    <div class="Menu-Categiories-Container6 Menu-Categiories-Container"><h3>DESSERTS</h3></div>
                    <div class="Menu-Categiories-Container7 Menu-Categiories-Container"><h3>BEVERAGES</h3></div>
                    <div class="Menu-Categiories-Container8 Menu-Categiories-Container"><h3>SPECIALS</h3></div>
                    <div class="Menu-Categiories-Container9 Menu-Categiories-Container"><i class="awesome fa-solid fa-seedling"></i><h4>Vegetarian</h4></div> 
                    <div class="Menu-Categiories-Container10 Menu-Categiories-Container"><i class="awesome fa-solid fa-wheat-awn"></i><h4>Gluten Free</h4></div>
                    <div class="Menu-Categiories-Container11 Menu-Categiories-Container"><i class="awesome fa-solid fa-cow"></i><h4>Dairy Free</h4></div>
                    <div class="Menu-Categiories-Container12 Menu-Categiories-Container"><i class="awesome fa-solid fa-bacon"></i><h4>Keto Friendly</h4></div> 
                </div>

    </div>
    <div class="Ordering-BG">
        <div class="container">
            <div class="OrderInApp">
                <h3>Download Our</h3>
                <h2>Ordering App</h2>
                <button><img src="../../assets/img/google-play.png" alt=""></button>
                <button class="apple"><img src="../../assets/img/apple-store.png" alt=""></button>
            </div>
        </div>
    </div>
    <div class="container">
        <div class="Bottom-Main">
            <h2>Menu Categories</h2> 
            <button class="order orderfix">WIEW THE FULL MENU <i class="arrow-left fa-solid fa-circle-arrow-right"></i> </button>
        </div>
        <div class="News">
            <div class="News1">
            <img src="../../assets/img/pancake-burger.jpg" alt="">
            <h3>NEW: The Pancake Burger</h3>
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis architecto eius totam deleniti voluptas nostrum recusandae pariatur voluptates suscipit</span>
            </div>
            <div class="News2">
            <img src="../../assets/img/new-milkshake-menu.jpg" alt="">
            <h3>New Milkshake Menu</h3>
            <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae maiores mollitia, vero voluptates dolore consequatur aliquid quod delectus, voluptate excepturi totam explicabo omnis quas dignissimos quis consectetur cum iusto optio?</span>
            </div>
        </div>
    </div>
</div>
  
</template>

<script>
export default {
    name: "BaseMain",
}
</script>

<style lang="scss" scoped>
    .order{
        margin-top: 50px;
        border-radius: 20px;
        background-color:red;
        color: white;
        border: none;
        width: 300px;
        height: 40px;
        }
.Dishes{
    display: flex;
    justify-content: center;
    margin-top: 150px;
}
.Top-Main{
    display: flex;
    justify-content: center;
    gap: 20px;
    img{
        margin-top: 20px;
        width: 300px;
        height: 400px;
    }
    h3{
        margin-top: 20px;
    }
    span{
        color: red;
    }
    .fry{
        h3{
            margin-left: 70px;
        }
        span{
            margin-left: 90px;
        }
    }
    .frap{
        h3{
            margin-left: 20px;
        }
        span{
            margin-left: 120px;
        }
    }
    .donut{
        h3{
            margin-left: 45px;
        }
        span{
            margin-left: 120px;
        }
    }
    .arrow-left{ 
    margin-left: 40px;
    }
}
.Wave{
    margin-bottom: 200px;
    height: 450px;
    background-image: url("../../assets/img/wave.svg"), url("../../assets/img/easy.jpg");
    background-size: cover;

}
.Mid-Main{
    display: flex;
    justify-content: space-between;
}
.Mid-Main-Photo{
    text-align: center;
    color: white;
    margin-top: 50px;
    display:flex;
    justify-content: center;
    flex-wrap: wrap;
    gap:20px;
    .Menu-Categiories-Container1{
        background-image: url("../../assets/img/appetizers-menu-background.jpg");
    }
    .Menu-Categiories-Container2{
        background-image: url("../../assets/img/burgers-menu-background.jpg");
    }
    .Menu-Categiories-Container3{
        background-image: url("../../assets/img/pizza-menu-background.jpg");
    }
    .Menu-Categiories-Container4{
        background-image: url("../../assets/img/fries-menu-background.jpg");
    }
    .Menu-Categiories-Container5{
        background-image: url("../../assets/img/sides-menu-background.jpg");
    }
    .Menu-Categiories-Container6{
        background-image: url("../../assets/img/desserts-menu-background.jpg");
    }
    .Menu-Categiories-Container7{
        background-image: url("../../assets/img/beverages-menu-background.jpg");
    }
    .Menu-Categiories-Container8{
        background-image: url("../../assets/img/specials-menu-background.jpg");
    }
    .Menu-Categiories-Container9{
        color: greenyellow;

    }
    .Menu-Categiories-Container10{
        color: gold;

    }
    .Menu-Categiories-Container11{
        color: skyblue;

    }
    .Menu-Categiories-Container12{
        color: brown;

    }
    h3{margin-top: 28%;}
    .awesome{
        margin-top: 28%;
        font-size: 30px;
    }
    h4{
        margin-top: 30px;
        color: black;
    }

}

.Menu-Categiories-Container{
    width: 300px;
    height: 200px;
    background-size:cover;

}
.Ordering-BG{
    margin-top:250px ;
    height: 600px;
    background-image: url("../../assets/img/app-ordering-scaled.jpg");
    background-size: cover;
    background-repeat: no-repeat ;
}
.OrderInApp{
    padding-top: 200px;
       button{
    background-color: transparent;
    border: none;
    img{
      width: 180px;
      height: 50px;
    }
  }
    h2{
        font-size: 70px;
        color: gold;
        margin-top: -20px;
        margin-bottom: 100px;
    }
    h3{
        font-size: 40px ;
        color: white;
    }
    .apple{
        margin-left: 20px;
    }
}
.Bottom-Main{
    margin-top: 100px;
    display: flex;
    justify-content: space-between;
    .orderfix{
        margin-top: 0;
    }
}
.News{
    display: flex;
    justify-content: center;
    gap: 30px;
    h3{
        margin-top: 30px;
        margin-left: 120px;
    }
    img{
        
        margin-top: 100px;
        width: 550px;
        height: 350px;
    }
    .News1{
        width: 550px;
    }
    .News2{
        width: 550px;
    }
}
</style>