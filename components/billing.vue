<template>
    <div class="main">
        <div>
            <h1>Billing address</h1>
            <p>Edit</p>
            <div>
                <div class="tableTop">
                    <p id="text1">First Name</p>
                    <p id="text2">Sabri</p>
                </div>
                <div v-for="item in Datas" :key="item.Text1" class="table">
                    <p id="text1">{{ item.Text1 }}</p>
                    <p id="text2">{{ item.Text2 }}</p>
                </div>
                <div class="tableBtm">
                    <p id="text1">Email Address</p>
                    <p id="text2">sabrihakuli@outlook.com</p>
                </div>
            </div>
        </div>
        <div>
            <h1 class="space">Your order</h1>
            <div>
                <div class="table2top">
                    <div><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</div>
                    <p id="x">x</p>
                </div>
                <div class="table2">
                    <div><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</div>
                    <p id="x">x</p>
                </div>
                <div class="table2btm">
                    <div><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</div>
                    <p id="x">x</p>
                </div>
            </div>
            <div class="black">
                <div class="table3top"> 
                    <p id="text3">Subtotal</p>
                    <p id="text4">€ 89,99 </p>
                </div>
                <div class="table3">
                    <p id="text3">Discount Cupon</p>
                    <p id="text4">€ 89,99 </p>
                </div>
                <div class="table3btm">
                    <p id="text5">Total</p>
                    <p id="text6">€ 89,99 </p>
                </div>
            </div>
            <div class="softPay">
                <div>
                    <div class="top">
                        <a-checkbox @change="onChange">
                            Soforte Payment
                        </a-checkbox>
                    </div>
                    <div>
                        <button class="button2">Go to soforte</button>
                    </div>
                </div>
                <div>
                    <img src="~assets/pic/mastercard.png" id="miniimgcard">
                    <img src="~assets/pic/amex.png" id="miniimgcard">
                    <img src="~assets/pic/visa.png" id="miniimgcard">
                    <img src="~assets/pic/diners.png" id="miniimgcard">
                    <img src="~assets/pic/jcb.png" id="miniimgcard">
                    <img src="~assets/pic/discover.png" id="miniimgcard">
                </div>
            </div>
            <div class="table4">
                <a-checkbox @change="onChange">
                    <img src="~assets/pic/Paypal 1.png" id="miniimgpaypal">
                </a-checkbox>
            </div>
            <div class="table5">
                <div class="top">
                    <a-checkbox @change="onChange">
                        I have read and agree to the website terms and conditions
                    </a-checkbox>
                </div>
                <div>
                    <button class="big">Place order</button>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
  
  data() {
    return{
      Datas: [{
        Text1: 'Last Name',
        Text2: 'Hakuli'
      },{
        Text1: 'Country',
        Text2: 'Kosovo'
      },{
        Text1: 'Street Address',
        Text2: 'Chuck Norris 32'
      },{
        Text1: 'Town',
        Text2: 'Gjilan'
      },{
        Text1: 'State',
        Text2: 'Gjilan'
      },{
        Text1: 'Postal Code',
        Text2: '60000'
      },{
        Text1: 'Phone',
        Text2: '+383 44 201 874'
      },
      ],
    }
  }
}
</script>
<style scoped>
.main{
    height: 1335px;
    width: 1440px;
    padding: 60px 110px 0px 110px;
    display: grid;
    grid-template-columns: 1fr 1fr;
}
h1 {
  color: #0B0B0C;
  font-size: 35px;
  padding-bottom: 25px;
}
#text1{
    color: #8786AD;
    padding-left: 19px;
}
#text2{
    color: #0B0B0C;
    text-align: right;
    padding-right: 19px;
}
#text3{
    color: #8786AD;
    padding-left:24px;
}
#text4{
    color: #8786AD;
    text-align: right;
    padding-right: 26px;
}
#text5{
    padding-left: 24px;
}
#text6{
    text-align: right;
    padding-right: 26px;
}
.table{
    width: 530px;
    height: 65px;
    border: 1px solid #EBEBEB;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.tableTop{
    width: 530px;
    height: 65px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
    margin-top: 25px;
}
.tableBtm{
    width: 530px;
    height: 65px;
    border: 1px solid #EBEBEB;
    border-radius: 0px 0px 10px 10px;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.table2top{
    width: 600px;
    height: 94px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-left: 18px;
    padding-top: 30px;
}
.table2{
    width: 600px;
    height: 94px;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-left: 18px;
    padding-top: 30px;
}
.table2btm{
    width: 600px;
    height: 94px;
    border: 1px solid #EBEBEB;
    border-radius: 0px 0px 10px 10px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-left: 18px;
    padding-top: 30px;
    margin-bottom: 50px;
}
.table3top{
    width: 600px;
    height: 65px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.table3{
    width: 600px;
    height: 65px;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.table3btm{
    width: 600px;
    height: 65px;
    border: 1px solid #EBEBEB;
    background-color: #0FAFE91A;
    border-radius: 0px 0px 10px 10px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
    margin-bottom: 50px;
}
.softPay{
    width: 600px;
    height: 200px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    display: grid;
    grid-template-columns: 1fr 120px;
    padding-top: 30px;
    padding-left: 27px;
}
.top{
    padding-top: 10px;
}
.big{
    width: 550px;
    height: 60px;
    margin-top: 50px;
}
.table4{
    width: 600px;
    height: 65px;
    border: 1px solid #EBEBEB;
    padding-top: 20px;
    padding-left: 27px;
}
.table5{
    width: 600px;
    height: 181px;
    border: 1px solid #EBEBEB;
    background-color: #0FAFE91A;
    border-radius: 0px 0px 10px 10px;
    padding-top: 20px;
    padding-left: 25px;
}
button {
  height: 60px;
  width: 260px;
}
.button2 {
  height: 60px;
  width: 260px;
  text-align: center;
  background-color: #0FAFE91A;
  color: #0FAFE9;
  cursor: pointer;
  border: 1px solid #0fafe9;
  border-radius: 10px;
  font-size: 15px;
  margin-top: 50px;
}
.black p{
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
}
#miniimgcard{
    height: 21px;
    width: 27px;
    margin-right: 8px;
    margin-bottom: 8.24px;
}
#miniimgpaypal{
    height: 16px;
    width: 48px;
    margin-left: 10px;
}
#x{
    text-align: right;
    color: #B9B9B9;
    padding-right: 28px;
}
.space{
    padding-bottom: 72px;
}
p{
    color:#0FAFE9;
    font-size: 15px;
}
</style>