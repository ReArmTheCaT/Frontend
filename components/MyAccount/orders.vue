<template>
    <div class="main">
        <div>
            <table cellspacing="0">
            <tr>
                <td id="first">My Profile</td>     
            </tr>
            <tr>
                <td>Dashboard</td>     
            </tr>
            <tr>
                <td id="highlight">Orders</td>  
            </tr>
            <tr>
                <td>Address</td>  
            </tr>
            <tr>
                <td>Account details</td>    
            </tr>
            <tr>
                <td id="btmb">Logout</td>     
            </tr>
        </table>
        </div>
        <div class="table">
            <h1>Orders</h1>
            <table cellspacing="0">
            <tr id="h2">
                <th id="col1">Order name</th>
                <th id="col2">Order ID</th>
                <th id="col3">Status</th>
                <th id="col4">QTY</th>
                <th id="col5">Total</th>
                <th id="col6"></th>
                <th id="col7"></th>
            </tr>
            <tr>
                <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                <td>#2306</td>
                <td>Processing </td>
                <td id="center">1</td>
                <td id="right">€ 89,99</td>
                <td id="centerde">DETAILS</td>
                <td><button>Download</button></td>
            </tr>
            <tr>
                <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                <td>#2306</td>
                <td>Processing </td>
                <td id="center">1</td>
                <td id="right">€ 89,99</td>
                <td id="centerde">DETAILS</td>
                <td><button>Download</button></td>
            </tr>
            <tr>
                <td><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</td>
                <td>#2306</td>
                <td>Processing </td>
                <td id="center">1</td>
                <td id="right">€ 89,99</td>
                <td id="centerde">DETAILS</td>
                <td><button>Download</button></td>
            </tr>
            </table> 
        </div>
    </div>
</template>
<style scoped>
.main{
    width: 1440px;
    padding: 50px 110px 0px 110px;
    display: grid;
    grid-template-columns: 290px 1fr;
    position: relative;
    grid-gap: 50px;
    padding-bottom: 100px;
}
table{
    border: 1px solid #EBEBEB;
    border-radius: 10px;
    border-collapse: separate;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
}
td{
    height: 65px;
    color: #0B0B0C;
    border-bottom: 1px solid #EBEBEB;
}
td:first-child{
    padding-left: 25px;
}
button {
  height: 50px;
  width: 140px;
  text-align: center;
  background-color: #0fafe9;
  color: white;
  cursor: pointer;
  border: 1px solid #0fafe9;
  border-radius: 10px;
  font-size: 15px;
}
h1{
    padding-bottom: 50px;
}
.table td{
    height: 94px;
}
.table th{
    height: 65px;
    font-size: 15px;
    font-weight: normal;
    background-color: rgba(15, 175, 233, 0.1);
}
th:first-child{
    padding-left: 27.7px;
    border-radius: 9px 0px 0px 0px;;
}
th:last-child{
    border-radius: 0px 9px 0px 0px;;
}
#btmb{
    border: none;
    color: #FF1D0E;
    border-radius: 0px 0px 0px 9px;
    width: 440px;
}
#first{
    height: 77px;
    font-size: 30px;
    color: white;
    background-color: #0FAFE9;
    border-radius: 9px 9px 0px 0px;
}
#highlight{
    background-color: rgba(15, 175, 233, 0.1);
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
}
#col1{
    width: 217px;
}
#col2{
    width: 97px;
    text-align: left;
}
#col3{
    width: 124px;
}
#col4{
    width: 86px;
    text-align: center;
}
#col5{
    width: 92px;
    text-align: right;
}
#col6{
    width: 116px;
}
#col7{
    width: 170px;
}
#center{
   text-align: center;
}
#centerde{
    text-align: center;
    color: #525F7F;
}
#right{
    text-align: right;
}
</style>