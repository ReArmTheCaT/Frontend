<template>
    <div class="main">
        <div>
            <div class="tabletop">
                <h1>My Profile</h1>
            </div>
            <div class="table">
                <nuxt-link to="/MyAccountDashboard" class="black">
                Dashboard
                </nuxt-link>
            </div>
            <div class="table">
                <nuxt-link to="/MyAccountOrder" class="black">
                Orders
                </nuxt-link>
            </div>
            <div class="table">
                <nuxt-link to="/MyAccountAddress" class="black">
                Address
                </nuxt-link>
            </div>
            <div id="highlight">
                <nuxt-link to="/MyAccountDetails" class="black">
                Account details
                </nuxt-link>
            </div>
            <div id="btmb">
                Logout
            </div>
        </div>
        <div>
            <h1>Account Details</h1>
            <div class="topBlock">
                <h2>FIRST NAME</h2>
                <h2>LAST NAME</h2>
                <div>
                    <a-input class="blueBox" placeholder="Sabri" size="large"/>
                </div>
                <div>
                    <a-input class="blueBox" placeholder="Last Name" size="large"/>
                </div>
            </div>
            <h2>DISPLAY NAME</h2>
            <div class="inputBox">
                <a-input class="inputBox" placeholder="Sabri Hakuli" size="large"/>
            </div>
            <h2>EMAIL ADDRESS</h2>
            <div class="inputBox">
                <a-input class="inputBox" placeholder="sabrihakuli@outlook.com" size="large"/>
            </div>
            <h1 id="h1">Change Password</h1>
            <h2>CURRENT PASSWORD</h2>
            <div class="inputBox">
                <a-input  class="inputBox" placeholder="********" size="large"/>
            </div>
            <h2>NEW PASSWORD</h2>
            <div class="inputBox">
                <a-input class="inputBox" placeholder="**************" size="large"/>
            </div>
            <h2>COMFIRM NEW PASSWORD</h2>
            <div class="inputBox">
                <a-input class="inputBox" placeholder="**************" size="large"/>
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
  display: grid;
  align-items: center;
  border-radius: 7px;
  margin-bottom: 30px;
  color: #B9B9B9;
}
.blueBox{
    height: 60px;
    width: 420px;
    display: grid;
    align-items: center;
    border-radius: 7px;
    margin-bottom: 30px;
    color: #0B0B0C;
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
.tabletop{
    width: 290px;
    height: 77px;
    border-radius: 10px 10px 0px 0px;
    background-color: #0FAFE9;
}
.tabletop h1{
    color: #FFFFFF;
    padding-top: 15px;
    padding-left: 25px;
    font-size: 30px;
}
.table{
    width: 290px;
    height: 65px;
    border: 1px solid #EBEBEB;
    padding-left: 18px;
    padding-top: 20px;
}
.black{
    color: #0B0B0C;
}
#btmb{
    width: 290px;
    height: 65px;
    border: 1px solid #EBEBEB;
    color: #FF1D0E;
    padding-left: 18px;
    padding-top: 20px;
}
#highlight{
    width: 290px;
    height: 65px;
    border: 1px solid #EBEBEB;
    background-color: rgba(15, 175, 233, 0.1);
    padding-left: 18px;
    padding-top: 20px;
}
#h1{
    padding-top: 20px;
    padding-bottom: 25px;
}
</style>
