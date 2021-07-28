<template>
<div class="bg">
    <headerTMP/>
    <div class="main">
            <div class="container">
                <div class="wrapper">
                    <div class="content">
                        <div class="title">Онлайн-кинотеатр IVI</div>
                        <div class="sub-title"><div class="sub-flex"><div>Более 100 000 фильмов и сериалов</div> <div class="tooltip"><span>единиц контента</span></div></div>
                        <div class="sub-flex"><div class="">с бесплатным трафиком на 5-ти устройствах</div> <img width="15px" height="15px" src="../assets/_.png" alt=""></div>
                </div>

            <div class="btns">
            <div class="btn"><span>Бесплатно на 14 дней</span></div>
            <div class="btn-right"><span>Как подключить?</span><img src="../assets/Play.png" alt=""></div>

            </div>
                    </div>
                    <img height="533px" width="690px" src="../assets/bg.png" alt="">
                </div>
            </div>
    </div>
</div>
</template>

<script>
import headerTMP from './Header.vue'
export default {
    components:{
        headerTMP
    }
}
</script>
<style scoped>

.btns{
    display: flex;
    align-items: center;
    gap: 20px;
}
.btn{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 130%;
/* identical to box height, or 26px */

display: flex;
align-items: center;
justify-content: center;
color: #FFFFFF;
    width: 292px;
height: 72px;

background: #FF0F52;
border-radius: 16px;

}
.btn-right{
        font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 130%;
/* identical to box height, or 26px */
display: flex;
align-items: center;
color: #FFFFFF;
width: 210px;
height: 72px;
gap:10px;

}
.sub-flex{
    display: flex;
    white-space: nowrap;
}
.tooltip{
    border-radius: 10px;
    width: 80px;
    height: 15px;
    display: flex;
    align-items: center;
    justify-content: center;
    border: 1px solid #fff;
}
.tooltip span{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 8px;
line-height: 144%;

}
.sub-title{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 132%;
/* or 26px */


/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.title{
    white-space: nowrap;
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 42px;
line-height: 52px;
/* identical to box height, or 124% */

/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.bg{

 background: linear-gradient(143.04deg, #FF0F52 -6.84%, #1B143B 68.79%);
}
.main{
    width: 100%;
height:100vh ;
 display: flex;
 align-items: center;
 justify-content: center;
 flex-direction: column;
}
.container{
    width: 80%;
    height: 100%;
}
.wrapper{
    width: 100%;
    height: 80%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.content{
    display: flex;
    flex-direction: column;
    gap:20px;
}
@media screen and (max-width:1125px) {
    .wrapper{
        flex-direction: column-reverse;
         justify-content: center;
         gap: 0;
         align-items: center;
         padding: 50px 0 0 0;
    }
    .main{
        padding: 0 0 50px 0;
    }
    .content{
        margin-top: -100px;
    }
}

@media screen and (max-width:609px) {
   
    .container{
        width: 95%;
    }
    .btns{
        flex-direction: column;
    }
    .btn{
        width: 100%;
    }
}

@media screen and (max-width:500px) {
    .wrapper > img {
        width: 150%;
    }
    .content{
        width: 100%;
    }
    .content > .title{
        font-size: 32px;
        white-space:normal;
    }
      .content > .sub-title{
        font-size: 14px;
    }
}
</style>