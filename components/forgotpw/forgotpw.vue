<template>
    <div class="forgotpw">
        <h1>Forgot password</h1>
        <div class="text">
            <p>Lost your password? Please enter your username or email address.
            <br>You will receive a link to create a new password via email.</p>
        </div>
        <h2>USERNAME OR EMAIL</h2>
        <div class="inputBox">
            <a-input placeholder="sabrihakuli@outlook.com" size="large"/>
        </div>
        <button>Reset password</button>
    </div>
</template>

<style scoped>
.forgotpw{
    height: 580px;
    width: 1440px;
    padding: 60px 110px 0px 110px;
}
.inputBox {
    height: 60px;
    width: 500px;
    /* border: 1px solid #EBEBEB;
    display: grid;
    align-items: center;
    border-radius: 7px;
    margin-bottom: 30px; */
}
.text {
    height: 53px;
    width: 535px;
    margin-bottom: 50px;
}
.inputBox p{
    color: #B9B9B9;
    font-size: 15px;
    padding-left: 32px;
}
button{
    height: 60px;
    width: 195px;
    text-align: center;
    background-color: #0FAFE9;
    color: white;
    cursor: pointer;
    border: 1px solid #0FAFE9;
    border-radius: 10px;
    font-size: 15px;
}
h1{
    color: #0B0B0C;
    font-size: 35px;
    padding-bottom: 50px;
    /* padding-top: 60px; */
}
p{
    color: #8786AD;
    font-size: 15px;
}
h2{
    color: #636363;
    font-size: 12px;
    padding-bottom: 10px;
}
</style>