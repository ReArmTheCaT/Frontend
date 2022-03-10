<template>
<div class="main">
    <div>
        <table cellspacing="0">
            <tr>
                <td id="first">My Profile</td>     
            </tr>
            <tr>
                <td id="highlight">Dashboard</td>     
            </tr>
            <tr>
                <td>Orders</td>  
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
    <div>
        <h1>Dashboard</h1>
        <p>
            From your account dashboard you can view your recent orders, 
            manage your shipping and billing addresses, and edit your password and account details.
        </p>
        <div class="box">
            <div class="inthebox">
                <div>
                    <img src="~assets/pic/shopping-bag.png">
                </div>
                <h1>Orders</h1> 
            </div>
            <div class="inthebox">
                <div>
                    <img src="~assets/pic/map-pin.png">
                </div>
                <h1>Address</h1> 
            </div>
            <div class="inthebox">
                <div>
                    <img src="~assets/pic/user.png">
                </div>
                <h1>Acount details</h1> 
            </div>
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
p{
    color: #8786AD;
    padding: 16px 0px 30px 0px;
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
</style>