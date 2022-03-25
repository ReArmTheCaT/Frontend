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
            <div id="highlight">
                <nuxt-link to="/MyAccountOrder" class="black">
                Orders
                </nuxt-link>
            </div>
            <div class="table">
                <nuxt-link to="/MyAccountAddress" class="black">
                Address
                </nuxt-link>
            </div>
            <div class="table">
                <nuxt-link to="/MyAccountDetails" class="black">
                Account details
                </nuxt-link>
            </div>
            <div id="btmb">
                Logout
            </div>
        </div>
        <div>
            <h1>Orders</h1>
            <div>
                <div class="table2">
                    <p id="col1">Order name</p>
                    <p>Order ID</p>
                    <p>Status</p>
                    <p>QTY</p>
                    <p>Total</p>
                </div>
                <div v-for="item in Products" :key="item.Product" class="tablePic">
                    <div>
                        <img v-bind:src="item.Img" alt="" id="miniimgFooter">
                        {{ item.Product }}
                    </div>
                    <div>
                        {{ item.OrID }}
                    </div>
                    <div>
                        {{ item.Status }}
                    </div>
                    <div>
                        {{ item.QTY }}
                    </div>
                    <div>
                        {{ item.Total }}
                    </div>
                    <div>
                        {{ item.Detail }}
                    </div>
                    <button>Download</button>
                </div>
                <div class="tablePicBtm">
                    <div><img src="~assets/pic/Logo2.png" id="miniimgFooter">WireDugi</div>
                    <p>#2306</p>
                    <p>Processing</p>
                    <p>1</p>
                    <p>€ 89,99</p>
                    <p>DETAILS</p>
                    <button>Download</button>
                </div>
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
        Img: require('~/assets/pic/Logo2.png'),
        OrID: '#2306',
        Status: 'Processing',
        QTY: '1',
        Total: '€ 89,99',
        Detail: 'DETAILS',
      },{
        Product: 'WireDugi',
        Img: require('~/assets/pic/Logo2.png'),
        OrID: '#2306',
        Status: 'Processing',
        QTY: '1',
        Total: '€ 89,99',
        Detail: 'DETAILS',
      },
      ],
    }
  }
}
</script>
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
.table2{
    height: 65px;
    width: 880px;
    background-color: rgba(15, 175, 233, 0.1);
    display: grid;
    grid-template-columns: 217px 97px 124px 86px 92px 116px 170px;
    align-items: center;
    border-radius: 7px 7px 0px 0px;
    color: #33334F;
    margin-top: 50px;
}
.tablePic{
    height: 94px;
    width: 880px;
    background-color: #FFFFFF;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 217px 97px 124px 86px 92px 116px 170px;
    align-items: center;
    color: #33334F;
}
.tablePicBtm{
    height: 94px;
    width: 880px;
    background-color: #FFFFFF;
    border: 1px solid #EBEBEB;
    display: grid;
    grid-template-columns: 217px 97px 124px 86px 92px 116px 170px;
    align-items: center;
    border-radius: 0px 0px 7px 7px;
    color: #33334F;
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
#first{
    height: 77px;
    font-size: 30px;
    color: white;
    background-color: #0FAFE9;
    border-radius: 9px 9px 0px 0px;
}
#miniimgFooter{
    height: 34px;
    width: 38px;
    margin-right: 10px;
    margin-left: 30px;
}
#col1{
    width: 217px;
    padding-left: 28px;
}
</style>