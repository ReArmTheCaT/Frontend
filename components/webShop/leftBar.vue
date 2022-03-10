<template>
    <div class="main">
        <table cellspacing="0">
            <tr>
                <td id="first">Browse Categories</td>     
            </tr>
            <tr>
                <td id="highlight">Home</td>     
            </tr>
            <tr>
                <td>WordPress Themes</td>  
            </tr>
            <tr>
                <td>eCommerce Templates</td>  
            </tr>
            <tr>
                <td>Marketing Templates</td>    
            </tr>
            <tr>
                <td>CMS Templates</td>  
            </tr>
            <tr>
                <td>Site Templates</td>  
            </tr>
            <tr>
                <td id="btmb">Blogging</td>     
            </tr>
        </table>
        <div class="sub">
            <h1>Subscribe Newsletter</h1>
            <p>Get all the latest information on Events, Sales and Offers.</p>
            <div class="inputBox">
                <p>Email address</p>
            </div>
            <button>SUBSCRIBE</button>
        </div>
        <div class="process">
            <a-progress type="circle" :percent="50" :width="120" :format="() => '+26%'"/>
            <h1>Monthly users in your site</h1>
            <h2>1.0286</h2>
            <p>We accompany you with our versatile expertise in digital marketing</p>
        </div>
        <div class="ads">
            <img src="~assets/pic/ads.png">
            <p>Create your beautiful portfolio website with Squarespace. Start your free trial.</p>
            <p id="gray">ads via Carbon</p>
        </div>
    </div>
</template>
<style scoped>
.main{
    width: 340px;
    /* margin-left: 110px; */
}
.sub{
    width: 340px;
    height: 283px;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 10px;
    align-items: center;
    text-align: center;
    margin: 20px 0px;
}
.inputBox {
  height: 60px;
  width: 308px;
  border: 1px solid #ebebeb;
  border-radius: 7px;
  background-color: #FFFFFF;
  text-align: left;
  padding: 16px 0px 20px 55px;
  margin: 16px 0px 20px 16px;
  color: #B9B9B9;
}
.process{
    width: 340px;
    height: 332px;
    border: 1px solid #ebebeb;
    border-radius: 10px;
    align-items: center;
    text-align: center;
}
table{
    border: 1px solid #EBEBEB;
    border-radius: 10px;
    border-collapse: separate;
    font-size: 15px;
    color: #0B0B0C;
    font-weight: normal;
    width: 340px;
}
td{
    height: 65px;
    padding-left: 25px;
    color: #0B0B0C;
    border-bottom: 1px solid #EBEBEB;
}
img{
    width: 340px;
    height: 106px;
}
button {
  height: 60px;
  width: 258px;
  text-align: center;
  background-color: rgba(15, 175, 233, 0.1);
  color: #0FAFE9;
  cursor: pointer;
  border: 1px solid #0fafe9;
  border-radius: 10px;
  font-size: 15px;
}
.sub h1{
    font-size: 18px;
    padding-top: 24px;
}
.process h1{
    font-size: 20px;
    color: #33334F;
}
.process h2{
    font-size: 35px;
    color: #0FAFE9;
    padding: 16px;
}
.process p{
    color: #B9B9B9;
    font-size: 15px;
    padding: 0px 10px;
}
.ads{
    width: 340px;
    height: 294px;
    background: rgba(248, 197, 41, 0.12);
    border-radius: 10px;
    text-align: center;
    margin-top: 20px;
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
#btmb{
    border: none;
    border-radius: 0px 0px 0px 9px;
    width: 440px;
}
.ads p{
    font-size: 15px;
    color: #33334F;
    padding-top: 48px;
}
#gray{
    color:#9F9F9F;
}
div.ant-progress-circle,
div.ant-progress-line {
  margin-top: 20px;
  margin-bottom: 16px;
}
</style>