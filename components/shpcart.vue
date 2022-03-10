<template>
    <div>
        <h1>Shopping Card</h1>
    <div class="main">
        <div>
        <table cellspacing="0">
            <tr id="h2">
            <th id="col1">Products</th>
            <th id="col2">Price</th>
            <th id="col3">Quantity</th>
            <th id="col4">Suptotal</th>
        </tr>
        <tr id="h1">
            <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
            <td>#2306</td>
            <td id="center">1</td>
            <td id="right">€ 89,99 </td>
        </tr>
        <tr id="h1">
            <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
            <td>#2306</td>
            <td id="center">1</td>
            <td id="right">€ 89,99 </td>
        </tr>
        <tr id="h1">
            <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
            <td>#2306</td>
            <td id="center">1</td>
            <td id="right">€ 89,99 </td>
        </tr>
        </table> 
        <div class="textbtm">
            <div class="textinput">
                <div class="white">
                    <p>Your discount code</p>
                </div>
                <div class="blue">
                    <p>Apply</p>
                </div>
            </div>
            <div>
                <p>If you have a coupon code discount please apply , 
                    otherwise please subscribe to our offers below for a chance to receive one. 
                </p>
            </div>
        </div>
        </div>
        <div class="pad">
            <table id="table2" cellspacing="0">
                <tr>
                    <td id="first">Card totals</td>
                    <td id="second"></td>      
                </tr>
                <tr>
                    <td>Subtotal</td>
                    <td id="col2v2">€ 89,99 </td>      
                </tr>
                <tr>
                    <td>Discount Cupon</td>
                    <td id="col2v2">€ 89,99 </td>      
                </tr>
                <tr>
                    <td id="btmb">Total</td>
                    <td id="col2btmb">€ 89,99 </td>      
                </tr>
            </table>
            <button>PROCEED TO CHECKOUT</button>
        </div>
    </div>
    </div>
</template>

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
.textbtm{
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: relative;
    grid-gap: 25px;
    padding-top: 25px;
}
.textinput{
    height: 60px;
    width: 428px;
    display: grid;
    grid-template-columns: 285px 1fr;
}
.white{
    height: 60px;
    width: 285px;
    border: 1px solid #EBEBEB;
    border-right: none;
    color: #B9B9B9;
    padding-left: 16px;
    display: grid;
    align-items: center;
    border-radius: 7px 0px 0px 7px;
}
.blue{
    height: 60px;
    width: 142px;
    display: grid;
    color: #0FAFE9;
    text-align: center;
    align-items: center;
    border: 1px solid #EBEBEB;
    border-left: none;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 7px 7px 0px;
}
table{
    border: 1px solid #EBEBEB;
    border-radius: 10px;
    border-collapse: separate;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
}
th{
    border-bottom: 1px solid #EBEBEB;
    font-weight: normal;
    padding-left: 25px;
}
h1{
    padding-left: 110px;
    /* padding-bottom: 50px; */
}
button {
  height: 60px;
  width: 260px;
  text-align: center;
  background-color: #0fafe9;
  color: white;
  cursor: pointer;
  border: 1px solid #0fafe9;
  border-radius: 10px;
  font-size: 15px;
  margin-top: 20px;
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
}
td{
    height: 65px;
    padding-left: 25px;
    color: #8786AD;
    border-bottom: 1px solid #EBEBEB;
}
#h1{
    height: 94px;
}
#h2{
    height: 65px;
    background-color: rgba(15, 175, 233, 0.1);
    /* border-radius: 10px 10px 0px 0px; */
}
#center{
    text-align: center;
}
#right{
    text-align: right;
    padding-right: 50px;
}
#col1{
    width: 485px;
}
#col2{
    width: 283px;
}
#col3{
    width: 200px;
    text-align: center;
}
#col4{
    width: 145px;
    text-align: right;
    padding-right: 50px;
}
#col2v2{
    width: 160px;
    text-align: right;
    padding-right: 20px;
}
#col2btmb{
    width: 160px;
    text-align: right;
    padding-right: 20px;
    border: none;
    color: #0B0B0C;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 0px 9px 0px;
}
#btmb{
    border: none;
    color: #0B0B0C;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 0px 0px 9px;
    width: 440px;
}
#first{
    height: 77px;
    font-size: 30px;
    color: white;
    background-color: #0FAFE9;
    border-radius: 9px 0px 0px 0px;
}
#second{
    background-color: #0FAFE9;
    border-radius: 0px 9px 0px 0px;
}
</style>