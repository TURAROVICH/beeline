<template>
    <div class="main">
        <div class="container">
            <div class="titles">
                  <div class="title">
                    Скачивайте приложение <span style="font-size:36px">Мой Beeline</span> 
                </div>
                <div class="des">
                    и получайте неограниченный доступ к миру кино и сериалов!
                </div>
            </div>
            <img src="../assets/iphone.png" alt="">
            <div class="content">
                <div class="title">
                    Скачивайте приложение Мой Beeline 
                </div>
                <div class="des">
                    и получайте неограниченный доступ к миру кино и сериалов!
                </div>

                <div class="btns">
                    <div class=" btn">
                        <img src="../assets/google-play.png" alt="">
                        <div class="btn-content">
                            <div class="des">Доступно в</div>
                            <div class="title">Google Play</div>
                        </div>
                    </div>

                     <div class="btn">
                       <svg width="20" height="25" viewBox="0 0 20 25" fill="#fff" xmlns="http://www.w3.org/2000/svg">
<path d="M16.745 13.1174C16.7721 11.2182 17.7581 9.46593 19.3564 8.47667C18.3535 7.00565 16.7241 6.10233 14.9621 6.04061C13.1131 5.84573 11.3182 7.16729 10.3757 7.16729C9.43316 7.16729 7.9744 6.06497 6.40757 6.09542C4.35173 6.16242 2.48108 7.31818 1.47898 9.1405C-0.652142 12.8799 0.938695 18.3793 2.97977 21.4C4.00031 22.886 5.19493 24.5364 6.75576 24.4451C8.31658 24.3537 8.85086 23.4585 10.6938 23.4585C12.5368 23.4585 13.0531 24.4451 14.6499 24.4085C16.2467 24.372 17.3213 22.9225 18.3058 21.4304C19.0261 20.3911 19.583 19.2447 19.9567 18.0321C18.0131 17.1936 16.7496 15.2601 16.745 13.1174Z" fill="#fff"/>
<path d="M13.7369 4.07959C14.6215 2.9882 15.0522 1.59008 14.9375 0.181885C13.5753 0.315368 12.3137 0.968346 11.4077 2.00893C10.5126 3.04213 10.059 4.39393 10.147 5.76656C11.5352 5.79172 12.8581 5.17003 13.7369 4.07959Z" fill="#ffffff"/>
</svg>

                        <div class="btn-content">
                            <div class="des">Доступно в</div>
                            <div class="title">App Store</div>
                        </div>
                    </div>
                </div>

                <div class="des-ivi">
                    Чтобы воспользоваться IVI, вам необходимо скачать приложение Мой Beeline. Затем нажать на кнопку IVI и безграничный мир кино и сериалов в ваших руках!
                </div>
                <div class="btn-play">
                        <span>Как подключить IVI навсегда?</span>
                        <img width="36" height="36" src="../assets/Play.png" alt="">
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
.titles{
    display: none;
}
.titles > .title{
    font-size: 32px;
}
.btn-play{
    width: 412px;
height: 72px;
justify-self: flex-start;
background: #FF0F52;
border-radius: 16px;
display: flex;
gap: 10px;
padding: 10px 20px;
align-items: center;
justify-content: center;
}
.btn-play span{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 20px;
line-height: 130%;
/* identical to box height, or 26px */

display: flex;
align-items: center;

color: #FFFFFF;
}
.des-ivi{
    /* Fira Sans regular 20px */
padding: 50px 0;
font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 132%;
/* or 26px */


color: #FFFFFF;
}
.btn-content{
    display: flex;
    align-items: center;
    gap: 0;
    flex-direction: column;
}
.btn{
    width: 160px;
height: 52px;
border-radius: 10px;
border: 1px solid #fff;
padding: 10px;
display: flex;
gap: 10px;
transition: all .9s ease;

}
.btn:hover{
    transition: all .9s ease;
    background: #FFCD00;
    border: none;
    color: #1A143B;
}
.btn-content .title{ 
    font-size: 16px;
font-weight: 500;
line-height: 18px;
}
.btn-content .des{
    font-size: 10px;
}
.btns{
    display: flex;
    gap: 10px;
    align-items: flex-start;
    justify-content: flex-start;
    width: 100%;
}
.main{
    background: #1A143B;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 70px 0;
}
.container{
    width: 80%;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
.title{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 42px;
line-height: 52px;
/* or 124% */


/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.content{
    display: flex;
    flex-direction: column;
    gap: 10px;
}
.des{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 20px;
line-height: 132%;
/* or 26px */


/* Color/Neutral/7 - White */

color: #FFFFFF;
}

@media screen and (max-width:1053px) {
    .container{
        width: 100%;
    }
}

@media screen and (max-width:950px) {
    .container{
       flex-direction: column;
       width: 80%;
    }
    .container > img{
        width: 100%;
    }
    .content > .title,.content > .des{
        display: none;
    }
    .content{
        gap: 0;
    }
    .titles{
        display: block;
    }
}

@media screen and (max-width:524px) {
    .container{
       width: 98%;
       justify-content: center;
       }
       .btns{
           justify-content: center;

       }
       .btn-play{
           width: 100%;
       }
}
</style>