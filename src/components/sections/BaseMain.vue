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
</div>
  
</template>

<script>
export default {
    name: "BaseMain",
}
</script>

<style lang="scss" scoped>
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
    .order{
        margin-top: 50px;
        border-radius: 20px;
        background-color:red;
        color: white;
        border: none;
        width: 300px;
        height: 40px;
        }
}
.Wave{
    height: 450px;
    background-image: url("../../assets/img/wave.svg"), url("../../assets/img/easy.jpg");
    background-size: cover;

}

</style>