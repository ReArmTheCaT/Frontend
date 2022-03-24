<template>
<div class="main">
    <div>
        <div class="tabletop">
            <h1>My Profile</h1>
        </div>
        <div id="highlight">
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
        <h1>Dashboard</h1>
        <p>
            From your account dashboard you can view your recent orders, 
            manage your shipping and billing addresses, and edit your password and account details.
        </p>
        <div class="box">
            <div  v-for="item in Boxes" :key="item.Text" class="inthebox">
                <div>
                    <img v-bind:src="item.Img" alt="" id="miniimgFooter">
                </div>
                <h1>{{ item.Text }}</h1> 
            </div>
        </div>
    </div>
</div>
</template>
<script>
export default {
  
  data() {
    return{
      Boxes: [{
        Text: 'Orders',
        Img: '~assets/pic/shopping-bag.png',
      },{
        Text: 'Address',
        Img: '~assets/pic/map-pin.png',
      },{
        Text: 'Acount details',
        Img: '~assets/pic/user.png',
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
.box{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    position: relative;
    grid-gap: 50px;
}
.inthebox{
    width: 260px;
    height: 200px;
    display: grid;
    grid-template-rows: 140px 1fr;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 10px;
    text-align: center;
}
img{
    width: 76px;
    height: 76px;
    margin-top: 47px;
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
p{
    color: #8786AD;
    padding: 16px 0px 30px 0px;
}
</style>