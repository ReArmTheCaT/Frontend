<template>
    <div class="main">
        <div class="text">
            <div>
                <h1>We build apps and websites</h1>
                <p>From multipurpose themes to niche templates,you'll always find something that catches your eye.</p>
            </div>
            <div class="button">
                <div>
                    <button>CONTRACT US</button>
                </div>
                <div>
                    <p>or see our portfolio</p>
                </div>
            </div>
        </div>
        <div>
            <img src="~assets/pic/phone.png">
        </div>
    </div>
</template>
<style scoped>
.main{
    width: 1220px;
    height: 316px;
    display: grid;
    grid-template-columns: 561.65px 1fr;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 10px;
    /* text-align: center; */
    margin: 100px 110px;
}
.text{
    width: 561.65px;
    height: 316px;
    display: grid;
    grid-template-rows: 197px 1fr;
}
p{
    font-size: 20px;
    padding-left: 40px;
}
h1{
    font-size: 35px;
    color: #0FAFE9;
    font-weight: bold;
    padding: 40px 0px 30px 40px;
}
.button{
    display: grid;
    grid-template-columns: 255px 1fr;
}
.button p{
    padding: 10px 0px 0px 0px;
    font-size: 18px;
}
button {
  height: 45px;
  width: 190px;
  text-align: center;
  background-color: #0fafe9;
  color: white;
  cursor: pointer;
  border: 1px solid #0fafe9;
  border-radius: 10px;
  font-size: 15px;
  margin-left: 40px;
}
img{
    width: 600px;
    height: 358px;
}
</style>