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
                    <td id="highlight">Address</td>  
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
            <h1>Address</h1>
            <h1 id="small">Billing address</h1>
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
    padding-left: 25px;
    color: #0B0B0C;
    border-bottom: 1px solid #EBEBEB;
}
h1{
    padding-bottom: 20px;
}
p{
    color:#0FAFE9;
    font-size: 15px;
    padding-bottom: 25px;
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
#col1{
    width: 440px;
    color: #8786AD;
}
#col2{
    width: 440px;
    padding-right: 33px;
    text-align: right;
}
#btm{
    border: none;
    color: #8786AD;
}
#col2btm{
    width: 244px;
    text-align: right;
    padding-right: 33px;
    border: none;
}
#small{
    font-size: 24px;
    padding-bottom: 25px;
}
</style>