<template>
    <div class="header">
        <div class="container">
            <div class="top-nav">
                <div class="links">
                    <div class="link">Помощь</div>
                    <div class="link">О компании</div>
                    <div class="link">Карта офисов</div>
                    <div class="link">Акции и новости</div>
                    <div class="link">Beeline Рахмат</div>
                </div>
                <div class="params">
                    <div class="lang"><span class="active">Рус</span>/<span>Кыр</span></div>
                    <div class="for lang"><span class="active">Частным лицам</span>/<span>Бизнесу</span></div>
                </div>
            </div>
            <div class="bottom-nav">
                <div @click="burger_active=!burger_active" class="burger">
                        <div class="burger-line" :class="{'burger-active':burger_active}"></div>
                        <div class="burger-line" :class="{'burger-active':burger_active}"></div>
                        <div class="burger-line" :class="{'burger-active':burger_active}"></div>

                    </div>
                <div class="bottom-left-nav">
                    
                <div class="logo"><img src="../assets/logo.png" alt=""></div>

                   <div class="links">
                    <div class="link">Перейти в Билайн </div>
                    <div class="link">Тарифы</div>
                    <div class="link">Услуги</div>
                    <div class="link">Пополнить баланс</div>
                    <div class="link">Приложения</div>
                    <div class="link">Еще</div>
                </div>
                </div>

                <div class="btn">
                    <span>Войти</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
 data:()=>({
     burger_active:false
 })    
}
</script>

<style scoped>
.burger{
    display: none;
}
.btn{
    width: 94px;
height: 44px;
display: grid;
place-content: center;
/* Color/Primary/1 - Yellow */
font-family: Fira Sans;
font-style: normal;
font-weight: 500;
font-size: 16px;
line-height: 144%;
background: #FFCD00;
border-radius: 8px;
}
.bottom-left-nav{
    display: flex;
    align-items: center;
    gap: 30px;
}
.bottom-nav{
    display: flex;
    align-items: center;
    justify-content: space-between;
}
.params{
    display: flex;
    gap: 20px;
    align-items: center;
}
.header{
     width: 100%;
      min-height: 128px; 
      
    display: flex;
    align-items: center;
    justify-content: center;
}
.container{
    width: 80%;
    height: 100%;
    display: flex;
    flex-direction: column;
    gap: 30px;
}
.top-nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.links{
    display: flex;
    align-items: center;
    gap:25px;
}
.link{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 144%;
/* or 20px */


/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.lang{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 17px;
color: #a19c9c;
}
.active{
    color: #FFFFFF;
}

@media (max-width:1000px) {
    .container{
        width: 95%;
    }
}
@media (max-width:858px) {
    .top-nav{
        display: none;
    }
    .links{
        display: none;
    }
    .burger{
        display: flex;
        flex-direction: column;
        gap: 10px;
        position: relative;
    }
    .burger-line{
        width: 40px;
        height: 5px;
        border-radius: 10px;
        background: #fff;
    }
    .burger-active:nth-child(1){
        transition: all 1s ease;
        transform: rotate(45deg);
        position:absolute;
        left: 0;
        top: 0;
    }
     .burger-active:nth-child(2){
        transition: all 1s ease;
        opacity: 0;
        width: 0;
        height: 0;
        visibility: hidden;
    }
     .burger-active:nth-child(3){
        transition: all 1s ease;
        transform: rotate(-45deg);
         position:absolute;
        left: 0;
        top: 0;

    }
}
</style>