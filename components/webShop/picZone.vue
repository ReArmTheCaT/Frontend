<template>
    <div>
        <div class="top">
            <div>
                <h1>Security Assurance</h1>
                <p>Our theme architecture is designed for maximize security and prevent malware, Dos Attack other. </p>
            </div>
            <div>
                <h1>Best Customer Support</h1>
                <p>Need help? We're here for you! Do not worry we provide in depth answer. </p>
            </div>
            <div>
                <h1>Great Quality Theme</h1>
                <p>We will be responsible for delivering the best online user experience, which makes my role extremely important.</p>
            </div>
        </div>
        <div class="line">
            <div>
                <img src="~assets/pic/image1.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <div  id="asd">
                    <img src="~assets/pic/image2.png" id="imgSelect">
                    <div class="selected">
                        <img src="~assets/pic/eye.png" id="miniimg">
                        <img src="~assets/pic/shpcart.png" id="miniimg">
                    </div>
                </div>
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image3.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
        </div>
        <div class="line">
            <div>
                <img src="~assets/pic/image4.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image5.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image6.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
        </div>
        <div class="line">
            <div>
                <img src="~assets/pic/image7.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image8.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image9.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
        </div>
        <div class="line">
            <div>
                <img src="~assets/pic/image10.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image11.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
            <div>
                <img src="~assets/pic/image12.png">
                <h1>RubICons</h1>
                <p id="gray">PHP, Wordpress</p>
                <p id="blue">$29,99</p>
            </div>
        </div>
    </div>
</template>
<style scoped>
.top{
    width: 863px;
    height: 250px;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 10px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    padding-left: 79px;
    /* margin-bottom: 48px; */
}
.top h1{
    font-size: 18px;
    color: #33334F;
    padding: 48px 0px 10px 0px;
    width: 190px;
    font-weight: bold;
}
.top p{
    font-size: 15px;
    color: #8786AD;
    width: 190px;
}
img{
    width: 276px;
    height: 180px;
    border-radius: 10px;
    margin-top: 50px;
}
.line{
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
}
.line h1{
    font-size: 18px;
    color: #0B0B0C;
    padding-top: 10px;
}
.selected{
    width: 130px;
    height: 42px;
    background-color: #FFFFFF;
    border-radius: 10px;
    position: absolute;
    top: 50%;
    left: 30%;
    /* transform: translate(-50%,-50%); */
}
#blue{
    font-size: 15px;
    color: #0FAFE9;
}
#gray{
    font-size: 12px;
    color: #B9B9B9;
}
#imgSelect{
    width: 276px;
    height: 180px;
    /* margin-bottom: 50px; */
    position: relative;
}
#asd{
    position: relative;
}
#miniimg{
    width: 20px;
    height: 17px;
    border-radius: 0px;
    margin: 12px 20px;
}
</style>