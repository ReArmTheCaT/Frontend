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
            <div class="table" id="highlight">
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
            <h1>Address</h1>
            <h1 id="small">Billing address</h1>
            <p>Edit</p>
            <div>
                <div class="table2Top">
                    <p id="text1">First Name</p>
                    <p id="text2">Sabri</p>
                </div>
                <div v-for="item in Datas" :key="item.Text1" class="table2">
                    <p id="text1">{{ item.Text1 }}</p>
                    <p id="text2">{{ item.Text2 }}</p>
                </div>
                <div class="table2Btm">
                    <p id="text1">Email Address</p>
                    <p id="text2">sabrihakuli@outlook.com</p>
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
    width: 1440px;
    padding: 50px 110px 0px 110px;
    display: grid;
    grid-template-columns: 290px 1fr;
    position: relative;
    grid-gap: 50px;
    padding-bottom: 100px;
}
h1{
    padding-bottom: 20px;
}
p{
    color:#0FAFE9;
    font-size: 15px;
    padding-bottom: 25px;
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
.table2{
    width: 880px;
    height: 65px;
    border: 1px solid #EBEBEB;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.table2Top{
    width: 880px;
    height: 65px;
    border: 1px solid #EBEBEB;
    border-radius: 10px 10px 0px 0px;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    display: grid;
    grid-template-columns: 1fr 1fr;
    padding-top: 20px;
}
.table2Btm{
    width: 880px;
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
.black{
    color: #0B0B0C;
}
#text1{
    color: #8786AD;
    padding-left: 32px;
}
#text2{
    color: #0B0B0C;
    text-align: right;
    padding-right: 32px;
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
#small{
    font-size: 24px;
    padding-bottom: 25px;
}
</style>