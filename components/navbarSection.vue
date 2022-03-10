<template>
    <div class="navbar">
        <img src="~assets/pic/Logo.png">
        <div>
            <ul>
                <li><a href="#">Browse</a><img src="~assets/pic/Vector.png" id="miniimg3"></li>
                <li><a href="#">All-Exclusive</a></li>
                <li><a href="#">Docs</a></li>
            </ul>
        </div>
        <div>
            <!-- <img src="~assets/pic/Heart.png" id="miniimg1"> -->
            <!-- <a-icon type="heart" :style="{ fontSize: '20px'}" id="miniimg1" /> -->
            <a-badge :count="1" id="miniimg1"> 
                <a-icon type="heart" :style="{ fontSize: '20px'}"/>
            </a-badge>
            <a-badge :count="5"> 
                <a-icon type="inbox"  :style="{ fontSize: '20px'}"/>
            </a-badge>
            <!-- <a-icon type="inbox"  :style="{ fontSize: '20px'}" id="miniimg2" /> -->
            <!-- <img src="~assets/pic/Card.png" id="miniimg2"> -->
      

            <button>Account</button>
        </div>
     </div>
</template>

<style scoped>
.navbar{
    height: 60px;    
    width: 1220px;
    display: grid;
    grid-template-columns: 185px 1fr 313px;
    margin: 40px 110px;
    align-items: center;
}

.navbar img{
    height: 48px;
    width: 135px;
}

#miniimg1{
    height: 20px;
    width: 20px;
    margin-right: 30px;
}
#miniimg2{
    height: 20px;
    width: 20px;
    margin-right: 5px;
}

#miniimg3{
    height: 3px;
    width: 6px;
    margin-top: 11.5px;
    margin-left: 8px;
}

a:link {
    color: #0B0B0C;
    background-color: transparent;
    text-decoration: none;  
}

a:visited {
    color: #0B0B0C;
    background-color: transparent;
    text-decoration: none;
}

.navbar ul {
    list-style-type: none;
    display: flex;
    background-color: #FFFFFF;
    margin-bottom: 0px;
}
.navbar li {
    display: flex;
    padding-right:30px;
}

button{
    height: 60px;
    width: 190px;
    text-align: center;
    background-color: #0FAFE9;
    color: white;
    cursor: pointer;
    border: 1px solid #0FAFE9;
    border-radius: 10px;
    font-size: 15px;
    margin-left: 40px;
}
    
</style>