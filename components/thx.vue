<template>
  <div class="thx">
    <h1>Thank you. Your plugin has been received.</h1>
    <div class="payment">
        <div>
            <p>Order number</p>
            <h2>6300</h2>
        </div>
        <div id="borderl">
            <p>Date</p>
            <h2>February 27, 2020</h2>
        </div>
        <div id="borderl">
            <p>Total</p>
            <h2>€ 69,99</h2>
        </div>
        <div id="borderl">
            <p>Payment method</p>
            <h2>Soforte Payment</h2>
        </div>
    </div>
    <h1>Order details</h1>
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
      <tr id="h2">
        <td id="left">Subtotal</td>
        <td></td>
        <td></td>
        <td id="right">€ 89,99 </td>
      </tr>
      <tr id="h2">
        <td id="left">Discount Cupon</td>
        <td></td>
        <td></td>
        <td id="right">€ 89,99 </td>
      </tr>
      <tr id="h2">
        <td id="left">Total</td>
        <td></td>
        <td></td>
        <td id="right">€ 89,99 </td>
      </tr>
    </table>
    <button>See your themes</button>
  </div>
</template>

<style scoped>
.thx{
    height: 1160px;
    width: 1440px;
    padding: 60px 110px 0px 110px;
}
table{
    border: 1px solid #EBEBEB;
    border-radius: 10px;
    border-collapse: separate;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
}
.payment{
    height: 82px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr;
    align-items: center;
    padding-bottom: 54px;
}
th{
    border-bottom: 1px solid #EBEBEB;
    font-weight: normal;
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
    margin-left: 50px;
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
td{
    border-bottom: 1px solid #EBEBEB;
}
#col1{
    width: 485px;
    padding-left: 50px;
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
#center{
    text-align: center;
}
#right{
    text-align: right;
    padding-right: 50px;
}
#left{
    padding-left: 50px;
}
#h1{
    height: 94px;
}
#h2{
    height: 65px;
    background-color: rgba(15, 175, 233, 0.1);
    /* border-radius: 10px 10px 0px 0px; */
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