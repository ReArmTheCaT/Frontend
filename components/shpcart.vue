<template>
    <div>
        <h1 id="h1">Shopping Card</h1>
        <div class="main">
            <div>
                <div class="table">
                    <p id="col1">Products</p>
                    <p>Price</p>
                    <p>Quantity</p>
                    <p>Suptotal</p>
                </div>
                <div v-for="item in Products" :key="item.Product" class="tablePic">
                    <div>
                        <img v-bind:src="item.img" alt="" id="miniimgFooter">
                        {{ item.Product }}
                    </div>
                    <div>
                        {{ item.Price }}
                    </div>
                    <div>
                        {{ item.Quli }}
                    </div>
                    <div>
                        {{ item.Supt }}
                    </div>
                </div>
                <div class="tablePicBtm">
                    <div><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</div>
                    <p>#2306</p>
                    <p>1</p>
                    <p>€ 89,99 </p>
                </div>
                <div class="apply">
                    <div>
                        <a-input-search
                        placeholder="Your discount code"
                        enter-button="apply"
                        size="large"
                        @search="onSearch"
                        />
                    </div>
                    <div>
                        <p id="p">If you have a coupon code discount please apply , 
                            otherwise please subscribe to our offers below for a chance to receive one. 
                        </p>
                    </div>
                </div>
            </div>
            <div>
                <div class="table2top">
                    <h1>Card totals</h1>
                </div>
                <div v-for="item in Totals" :key="item.text1" class="table2mid">
                    <div>{{ item.Text1 }}</div>
                    <div id="right">{{ item.Text2 }}</div>
                </div>
                <div class="table2btm">
                    <div>Total</div>
                    <div id="right">€ 89,99 </div>
                </div>
                <button>Proceed to checkout</button>
            </div>
        </div>
    </div>
</template>
<script>
export default {
  
  data() {
    return{
      Products: [{
        Product: 'WireDugi',
        Img: '~assets/pic/Logo2.png',
        Price: '#2306',
        Quli: '1',
        Supt: '€ 89,99 ',
      },{
        Product: 'WireDugi',
        Img: '~assets/pic/Logo2.png',
        Price: '#2306',
        Quli: '1',
        Supt: '€ 89,99 ',
      },
      ],
      Totals: [{
          Text1: 'Subtotal',
          Text2: '€ 89,99 ',
      },{
          Text1: 'Discount Cupon',
          Text2: '€ 89,99 ',
      },
      ]
    }
  }
}
</script>
<style scoped>
.main{
    /* height: 625px; */
    width: 1440px;
    padding: 50px 110px 0px 110px;
    display: grid;
    grid-template-columns: 811px 1fr;
    position: relative;
    grid-gap: 74px;
    padding-bottom: 100px;
}
.table{
    height: 65px;
    width: 811px;
    background-color: rgba(15, 175, 233, 0.1);
    display: grid;
    grid-template-columns: 385px 163px 120px 85px;
    align-items: center;
    border-radius: 7px 7px 0px 0px;
    color: #33334F;
}
.tablePic{
    height: 94px;
    width: 811px;
    background-color: #FFFFFF;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 385px 183px 100px 85px;
    align-items: center;
    color: #33334F;
}
.tablePicBtm{
    height: 94px;
    width: 811px;
    background-color: #FFFFFF;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 385px 183px 100px 85px;
    align-items: center;
    border-radius: 0px 0px 7px 7px;
    color: #33334F;
}
.apply{
    height: 60px;
    width: 811px;
    display: grid;
    grid-template-columns: 452px 1fr;
    padding-top: 25px;
}
.table2top{
    width: 335px;
    height: 77px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    background-color: #0FAFE9;
}
.table2top h1{
    color: #FFFFFF;
    padding-top: 15px;
    padding-left: 25px;
    font-size: 30px;
}
.table2mid{
    width: 335px;
    height: 65px;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
    padding-left: 25px;
    color: #8786AD;
}
.table2btm{
    width: 335px;
    height: 65px;
    border: 1px solid #EBEBEB;
    border-radius: 0px 0px 10px 10px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    background-color: rgba(15, 175, 233, 0.1);
    padding-top: 20px;
    padding-left: 25px;
    color: #0B0B0C;
    margin-bottom: 20px;
}
button{
    width: 335px;
    height: 60px;
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
    margin-left: 26px;
}
#right{
    text-align: right;
    padding-right: 27px;
}
#col1{
    width: 385px;
    padding-left: 50px;
}
#h1{
    padding-left: 110px;
}
#p{
    padding-left: 25px;
    color: #8786AD;
}
</style>