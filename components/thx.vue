<template>
  <div class="thx">
    <h1>Thank you. Your plugin has been received.</h1>
    <div class="payment">
      <div>
          <p>Order number</p>
          <h2>6300</h2>
      </div>
        <div v-for="item in Payments" :key="item.Text1" id="borderl">
            <p>{{ item.Text1 }}</p>
            <h2>{{ item.Text2 }}</h2>
        </div>
    </div>
    <h1>Order details</h1>
    <div class="table">
        <p id="col1">Products</p>
        <p>Price</p>
        <p>Quantity</p>
        <p>Suptotal</p>
    </div>
    <div v-for="item in Products" :key="item.Product" class="tablePic">
      <div>
        <img v-bind:src="item.Img" alt="" id="miniimgFooter">
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
    <div v-for="item in SubTotals" :key="item.Text" class="tableSub">
      <div>
        {{ item.Text }}
      </div>
      <div></div>
      <div></div>
      <div>
        {{ item.Price }}
      </div>
    </div>
    <div class="tableSub2">
      <div>
        Total
      </div>
      <div></div>
      <div></div>
      <div>
        € 89,99 
      </div>
    </div>
    <button>See your themes</button>
  </div>
</template>
<script>
export default {
  
  data() {
    return{
      Payments: [{
        Text1: 'Date',
        Text2: 'February 27, 2020'
      },{
        Text1: 'Total',
        Text2: '€ 69,99'
      },{
        Text1: 'Payment method',
        Text2: 'Soforte Payment'
      },
      ],
      Products: [{
        Product: 'WireDugi',
        Img: require('~/assets/pic/Logo2.png'),
        Price: '#2306',
        Quli: '1',
        Supt: '€ 89,99 ',
      },{
        Product: 'WireDugi',
        Img: require('~/assets/pic/Logo2.png'),
        Price: '#2306',
        Quli: '1',
        Supt: '€ 89,99 ',
      },{
        Product: 'WireDugi',
        Img: require('~/assets/pic/Logo2.png'),
        Price: '#2306',
        Quli: '1',
        Supt: '€ 89,99 ',
      },
      ],
      SubTotals:[{
        Text: 'Subtotal',
        Price: '€ 89,99 '
      },{
        Text: 'Discount Cupon',
        Price: '€ 89,99 '
      },
      ]
    }
  }
}
</script>
<style scoped>
.thx{
    height: 1160px;
    width: 1440px;
    padding: 60px 110px 0px 110px;
}
.payment{
    height: 82px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    align-items: center;
    padding-bottom: 54px;
}
.table{
    height: 65px;
    width: 1096px;
    background-color: rgba(15, 175, 233, 0.1);
    display: grid;
    grid-template-columns: 485px 283px 200px 185px;
    align-items: center;
    border-radius: 7px 7px 0px 0px;
}
.tablePic{
    height: 94px;
    width: 1096px;
    background-color: #FFFFFF;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 485px 283px 200px 185px;
    align-items: center;
}
.tableSub{
    height: 65px;
    width: 1096px;
    background-color: rgba(15, 175, 233, 0.1);
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 435px 283px 200px 185px;
    align-items: center;
    padding-left: 50px;
    color: #33334F;
}
.tableSub2{
    height: 65px;
    width: 1096px;
    background-color: rgba(15, 175, 233, 0.1);
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 435px 283px 200px 185px;
    border-radius: 0px 0px 7px 7px;
    align-items: center;
    padding-left: 50px;
    color: #0B0B0C;
}
img{
    height: 34px;
    width: 38px;
    margin-right: 10px;
    margin-left: 50px;
}
button {
  height: 60px;
  width: 260px;
  margin-top: 50px;
}
#col1{
    width: 485px;
    padding-left: 50px;
}

h1 {
  color: #0B0B0C;
  font-size: 35px;
  padding-bottom: 50px;
}
p {
  color: #8786AD;
  font-size: 15px;
}
h2{
    color: #0B0B0C;
    font-size: 20px;
    font-weight: 600;
}
#borderl{
    border-left: 1px solid #EBEBEB;
    padding-left: 72px;
}
</style>