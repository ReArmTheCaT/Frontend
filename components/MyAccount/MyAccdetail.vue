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
                <td>Orders</td>  
            </tr>
            <tr>
                <td>Address</td>  
            </tr>
            <tr>
                <td id="highlight">Account details</td>    
            </tr>
            <tr>
                <td id="btmb">Logout</td>     
            </tr>
        </table>
        </div>
        <div>
            <h1>Account Details</h1>
            <div class="topBlock">
                <h2>FIRST NAME</h2>
                <h2>LAST NAME</h2>
                <div class="blueBox">
                    <p>Sabri</p>
                </div>
                <div class="redBox">
                    <p>Last Name</p>
                </div>
            </div>
            <h2>DISPLAY NAME</h2>
            <div class="inputBox">
                <p>Sabri Hakuli</p>
            </div>
            <h2>EMAIL ADDRESS</h2>
            <div class="inputBox">
                <p>sabrihakuli@outlook.com</p>
            </div>
            <h1 id="h1">Change Password</h1>
            <h2>CURRENT PASSWORD</h2>
            <div class="inputBox">
                <p>********</p>
            </div>
            <h2>NEW PASSWORD</h2>
            <div class="inputBox">
                <p>**************</p>
            </div>
            <h2>COMFIRM NEW PASSWORD</h2>
            <div class="inputBox">
                <p>**************</p>
            </div>
            <div class="lastbtn">
                <button>SAVE CHANGES</button>
                <p>Reset</p>
            </div>
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
.inputBox {
  height: 60px;
  width: 880px;
  border: 1px solid #ebebeb;
  display: grid;
  align-items: center;
  border-radius: 7px;
  margin-bottom: 30px;
  padding-left: 25.85px;
  color: #B9B9B9;
}
.blueBox{
    height: 60px;
    width: 420px;
    border: 1px solid #0FAFE9;
    display: grid;
    align-items: center;
    border-radius: 7px;
    margin-bottom: 30px;
    padding-left: 25.85px;
    color: #0B0B0C;
}
.redBox{
    height: 60px;
    width: 420px;
    border: 1px solid #FF1D0E;
    display: grid;
    align-items: center;
    border-radius: 7px;
    margin-bottom: 30px;
    padding-left: 25.85px;
    color: #B9B9B9;
}
.lastbtn{
    display: grid;
    grid-template-columns: 310px 1fr;
    padding-top: 20px;
}
.lastbtn p{
    display: grid;
    grid-template-columns: 310px 1fr;
    color:#0FAFE9;
    font-size: 15px;
    padding-top: 20px;
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
    padding-left: 25px;
    color: #0B0B0C;
    border-bottom: 1px solid #EBEBEB;
}
h2 {
  color: #636363;
  font-size: 12px;
  padding-bottom: 10px;
}
h1{
    padding-bottom: 50px;
}
.topBlock{
    display: grid;
    grid-template-columns: 1fr 1fr;
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
#h1{
    padding-top: 20px;
    padding-bottom: 25px;
}
</style>