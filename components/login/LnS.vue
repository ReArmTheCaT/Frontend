<template>
  <div class="lnr">
    <div>
      <h1>Login</h1>
      <h2>USERNAME OR EMAIL ADDRESS</h2>
      <div class="inputBox">
        <a-input placeholder="sabrihakuli@outlook.com" size="large"/>
      </div>
      <h2>PASSWORD</h2>
      <div class="inputBox">
        <a-input placeholder="********************" size="large"/>
      </div>
      <div class="remember">
        <div>
            <button>LOGIN TO YOUR ACCOUNT</button>
        </div>
        <div>
            <a-checkbox @change="onChange" class="blue">
                Remember me
            </a-checkbox>
        </div>
      </div>
      <p>Lost your password?</p>
    </div>

    <div>
      <h1>Register</h1>
      <h2>USERNAME OR EMAIL ADDRESS</h2>
      <div class="inputBox">
        <a-input placeholder="sabrihakuli@outlook.com" size="large"/>
      </div>
      <p>
        A password will be sent to your email address.<br /><br />
        Your personal data will be used to support your experience throughout
        this website, to manage access to your account, and for other purposes
        described in our privacy policy.
      </p>
      <button>REGISTER</button>
    </div>
  </div>
</template>

<style scoped>
.lnr {
  height: 640px;
  width: 1440px;
  display: grid;
  grid-template-columns: 1fr 1fr;
  padding: 60px 110px 0px 110px;
  position: relative;
  grid-gap: 100px;
}
.inputBox {
  height: 60px;
  width: 500px;
  margin-bottom: 30px; 
}
.remember{
    display: grid;
    grid-template-columns: 276px 1fr;
    align-items: center;
    padding-bottom: 20px;
}
.checkbox{
    height: 22px;
    width: 22px;
    border: 1px solid #0FAFE9;
    border-radius: 7px;
}
.text {
  height: 53px;
  width: 535px;
  margin-bottom: 50px;
}
.inputBox p {
  color: #b9b9b9;
  font-size: 15px;
  padding-left: 24px;
  padding-bottom: 0px;
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
h1 {
  color: #0b0b0c;
  font-size: 35px;
  padding-bottom: 50px;
  /* padding-top: 60px; */
}
p {
  color: #656567;
  font-size: 15px;
  padding-bottom: 23px;
}
#textremem{
    padding-bottom: 0px;
    color: #0B0B0C;
}
h2 {
  color: #636363;
  font-size: 12px;
  padding-bottom: 10px;
}
</style>
