<template>
    <div class="main">
        <div>
            <h1>Billing address</h1>
            <p>Edit</p>
            <table cellspacing="0">
                <tr>
                    <td id="col1">First Name</td>
                    <td id="col2">Sabri</td>      
                </tr>
                <tr>
                    <td id="col1">Last Name</td>
                    <td id="col2">Hakuli</td>      
                </tr>
                <tr>
                    <td id="col1">Country</td>
                    <td id="col2">Kosovo</td>      
                </tr>
                <tr>
                    <td id="col1">Street Address</td>
                    <td id="col2">Chuck Norris 32</td>      
                </tr>
                <tr>
                    <td id="col1">Town</td>
                    <td id="col2">Gjilan</td>      
                </tr>
                <tr>
                    <td id="col1">State</td>
                    <td id="col2">Gjilan</td>      
                </tr>
                <tr>
                    <td id="col1">Postal Code</td>
                    <td id="col2">60000</td>      
                </tr>
                <tr>
                    <td id="col1">Phone</td>
                    <td id="col2">+383 44 201 874</td>      
                </tr>
                <tr>
                    <td id="btm">Email Address</td>
                    <td id="col2btm">sabrihakuli@outlook.com</td>      
                </tr>
            </table>
        </div>
        <div>
            <h1 class="space">Your order</h1>
            <table cellspacing="0">
                <tr>
                    <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                    <td id="x">x</td>      
                </tr>
                <tr>
                    <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                    <td id="x">x</td>      
                </tr>
                <tr>
                    <td id="btm2"><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                    <td id="xbtm">x</td>      
                </tr>
            </table>
            <table id="table2" cellspacing="0">
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
            <table cellspacing="0">
                <tr>
                    <td id="tdtable3">Soforte Payment<br>
                    <button class="button2">Go to soforte</button>
                    </td>
                    <td id="col2table3">
                        <img src="~assets/pic/mastercard.png" id="miniimgcard">
                        <img src="~assets/pic/amex.png" id="miniimgcard">
                        <img src="~assets/pic/visa.png" id="miniimgcard">
                        <img src="~assets/pic/diners.png" id="miniimgcard">
                        <img src="~assets/pic/jcb.png" id="miniimgcard">
                        <img src="~assets/pic/discover.png" id="miniimgcard">
                    </td>      
                </tr>
                <tr>
                    <td>
                        <img src="~assets/pic/Paypal 1.png" id="miniimgpaypal">
                    </td>
                    <td></td>      
                </tr>
                <tr>
                    <td id="left">
                        <div>I have read and agree to the website terms and conditions</div>
                        <div><button>Place order</button> </div>
                    </td>
                    <td id="right"></td>    
                </tr>
            </table>
        </div>
    </div>
</template>

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
#table2{
    color: #8786AD;
}
table{
    border: 1px solid #EBEBEB;
    border-radius: 10px;
    border-collapse: separate;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    margin-bottom: 50px;
}
td{
    border-bottom: 1px solid #EBEBEB;
    height: 64px;
    padding-left: 20px;
}
td:last-child{
    text-align: right;
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
  margin-top: 50px;
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
#btm{
    border: none;
    color: #8786AD;
}
#btmb{
    border: none;
    color: #0B0B0C;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 0px 0px 9px;
    width: 440px;
}
#btm2{
    border: none;
    width: 440px;
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
    margin-right: 8px;
}
#col1{
    width: 286px;
    color: #8786AD;
}
#col2{
    width: 244px;
    text-align: right;
    padding-right: 20px;
}
#col2v2{
    width: 160px;
    text-align: right;
    padding-right: 20px;
}
#col2btm{
    width: 244px;
    text-align: right;
    padding-right: 20px;
    border: none;
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
#x{
    width: 160px;
    text-align: right;
    padding-right: 20px;
    color: #B9B9B9;
}
#xbtm{
    width: 160px;
    text-align: right;
    padding-right: 20px;
    color: #B9B9B9;
    border: none;
}
#tdtable3{
    width: 440px;
}
#col2table3{
    width: 160px;
    height: 200px;
}
#left{
    height: 181px;
    text-align: left;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 0px 0px 9px;
}
#right{
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 0px 0px 9px 0px;
}
.space{
    padding-bottom: 72px;
}
p{
    color:#0FAFE9;
    font-size: 15px;
    padding-bottom: 25px;
}
</style>