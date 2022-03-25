<template>
    <div>
        <div class="top">
            <div v-for="item in Boxes" :key="item.Header" class="top_pic">
                <div class="blueBox">
                    <img v-bind:src="item.Img" alt="" id="miniimgFooter">
                </div>
                <div>
                    <h1>{{ item.Header }}</h1>
                    <p>{{ item.Content }}</p>
                </div>
            </div>
        </div>
        <div class="line">
            <div v-for="item in Pictures" :key="item.Header">
                <img v-bind:src="item.Img" alt="" class="img" >
                <h1 class="Pic">{{ item.Header }}</h1>
                <p id="gray">{{ item.Cate }}</p>
                <p id="blue">{{ item.Price }}</p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
  
  data() {
    return{
      Boxes: [{
        Img: require('~/assets/pic/top1.png'),
        Header: 'Security Assurance',
        Content: 'Our theme architecture is designed for maximize security and prevent malware, Dos Attack other. ',
      },{
        Img: require('~/assets/pic/top2.png'),
        Header: 'Best Customer Support',
        Content: 'Need help? We’re here for you! Do not worry we provide in depth answer. ',
      },{
        Img: require('~/assets/pic/top3.png'),
        Header: 'Great Quality Theme',
        Content: 'We will be responsible for delivering the best online user experience, which makes my role extremely important.',
      },
      ],
      Pictures:[{
          Img: require('~/assets/pic/Image1.png'),
          Header: 'RubICons',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image2.png'),
          Header: 'DugiLan',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image3.png'),
          Header: 'Abstract Theme',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image4.png'),
          Header: 'DugiCon',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image5.png'),
          Header: 'DugiApp',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image6.png'),
          Header: 'DugiOS',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image7.png'),
          Header: 'DugiUI',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image8.png'),
          Header: 'WireDugi',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image9.png'),
          Header: 'Dugico',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image10.png'),
          Header: 'UI Illustrations',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image11.png'),
          Header: 'Login Apps',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },{
          Img: require('~/assets/pic/Image12.png'),
          Header: 'Analysis app',
          Cate: 'PHP, Wordpress',
          Price: '$29,99',
      },
      ]
    }
  }
}
</script>
<style scoped>
.top{
    width: 863px;
    height: 250px;
    background-color: rgba(15, 175, 233, 0.1);
    border-radius: 10px;
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    padding-left: 29px;
    /* margin-bottom: 48px; */
}
.top h1{
    font-size: 18px;
    color: #33334F;
    padding: 0px 0px 10px 0px;
    width: 190px;
    font-weight: bold;
}
.top p{
    font-size: 15px;
    color: #8786AD;
    width: 190px;
}
.top_pic{
    display: grid;
    grid-template-columns: 50px 1fr;
    padding-top: 48px;
}
.blueBox{
    width: 40px;
    height: 40px;
    background-color: #0FAFE91A;
    border-radius: 10px;
    padding: 8px 11px;
}
.img{
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
.Pic:hover{
    color: #0FAFE9;
    cursor: pointer;
}
#blue{
    font-size: 15px;
    color: #0FAFE9;
}
#miniimgFooter{
    height: 17px;
    width: 17px;
}
#gray{
    font-size: 12px;
    color: #B9B9B9;
    text-transform: uppercase;
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