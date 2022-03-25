<template>
    <div class="main">
        <div class="more">
            <div>
                <h1>More than 100 Wordpress Themes & Templates</h1>
                <div class="textinput">
                    <div >
                        <a-input-search
                        placeholder="e.g Responsive slider"
                        enter-button="search"
                        size="large"
                        @search="onSearch"
                        class="test"
                        />
                    </div>
                </div>
                <p id="p20">From multipurpose themes to niche templates,you'll always find something that catches your eye.</p>
            </div>
            <div>
                <img src="~assets/pic/Photos.png" id="img">
            </div>
        </div>
        <div class="blueText">
            <p>SOME OF OUR 500 CLIENTS ALREADY USING DUGILAN</p>
        </div>
        <div class="com">
            <img src="~assets/pic/g1.png" id="acer">
            <img src="~assets/pic/g2.png" id="facebook">
            <img src="~assets/pic/g3.png" id="linkedin">
            <img src="~assets/pic/g4.png" id="fobes">
            <img src="~assets/pic/g5.png" id="dell">
        </div>
    </div>
</template>
<style scoped>
.main{
    width: 1220px;
    height: 706px;
    /* display: grid;
    grid-template-columns: 561.65px 1fr; */
    border-radius: 10px;
    margin: 0px 110px;
}
.more{
    height: 381px;
    width: 1220px;
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: relative;
    grid-gap: 40px;
}
.textinput{
    height: 60px;
    width: 570px;
    display: grid;
    margin: 45px 0px;
}
.white{
    height: 60px;
    width: 380px;
    border: 1px solid #EBEBEB;
    border-right: none;
    color: #B9B9B9;
    padding-left: 16px;
    display: grid;
    align-items: center;
    border-radius: 7px 0px 0px 7px;
}

.blue{
    height: 60px;
    width: 190px;
    display: grid;
    color: #FFFFFF;
    text-align: center;
    align-items: center;
    border: 1px solid #EBEBEB;
    border-left: none;
    background-color: #0FAFE9;
    border-radius: 0px 7px 7px 0px;
}
.blueText{
    color: #0FAFE9;
    text-align: center;
    font-size: 18px;
    font-weight: 600px;
    padding-top: 80px;
}
h1{
    font-size: 45px;
    font-weight: bold;
    color: #0B0B0C;
}
#img{
    width: 610px;
    height: 364px;
    border-radius: 10px;
}
.com{
    height: 70px;
    width: 1220px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
    position: relative;
    grid-gap: 30px;
    align-items: center;
    justify-items: center;
    padding-top: 30px;
}
#p20{
    font-size: 20px;
}
#acer{
    height: 24px;
    width: 92px;
}
#facebook{
    height: 24px;
    width: 103px;
}
#linkedin{
    height: 24px;
    width: 92px;
}
#fobes{
    height: 24px;
    width: 92px;
}
#dell{
    height: 24px;
    width: 92px;
}
</style>
<style>
.test .ant-btn-lg{
    height: 60px;
    width: 190px;
    background-color: #0FAFE9;
}
</style>