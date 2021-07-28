<template>
    <div class="main">
        <div class="container">
            <div class="title">
                Бесплатная и безлимитная подписка 
IVI навсегда — в вашем тарифе!
            </div>

            <div class="cards">
                    <div class="card">
                        <div class="card-header">
                            <img src="../assets/visual.png" alt="">
                            <div class="content">
                                <div class="card-header-title">
                                    Бирге для интернета + IVI
                                </div>
                                <div class="date">
                                    <span class="date-title">390с</span>
                                    <span class="date-des">/ неделя</span>
                                </div>
                            </div>
                        </div>

                        <div class="card-body">
                            <div class="card-body-title">
                                Активируйте подписку IVI в Мой Beeline
                            </div>
                            <div class="body-description">
                                <div class="body-mini-des">
                                    <div class="body-des-title">30 Гб </div>
                                    <div class="body-des">интернета</div>
                                </div>

                                 <div class="body-mini-des">
                                    <div class="body-des-title">10 Гб  </div>
                                    <div class="body-des"><span>на</span> <img src="../assets/ivi.png" alt=""></div>
                                </div>

                                  <div class="body-mini-des">
                                    <div class="body-des-title">10 мин  </div>
                                    <div class="body-des">на звонки вне сети</div>
                                </div>

                                 <div class="body-mini-des">
                                    <div class="body-des-title">2 Гб </div>
                                    <div class="body-des">
                                        <span>на</span>
                                        <img src="../assets/instagram.png" alt="">
                                        <img src="../assets/whatsapp.png" alt="">
                                        <img src="../assets/telegram.png" alt="">
                                    </div>
                                </div>
                            </div>

                            <div class="btn-container">
                                <div class="btn"><span>Подключить</span></div>
                                
                            <div class="btn-des">Получить SIM-карту</div>
                            </div>
                        </div>
                    </div>



                    <div class="card">
                        <div class="card-header">
                            <img src="../assets/visual1.png" alt="">
                            <div class="content">
                                <div class="card-header-title">
                                  Бирге для интернета
PRO + IVI
                                </div>
                                <div class="date">
                                    <span class="date-title">490с</span>
                                    <span class="date-des">/ неделя</span>
                                </div>
                            </div>
                        </div>

                        <div class="card-body">
                            <div class="card-body-title">
                                Активируйте подписку IVI в Мой Beeline
                            </div>
                            <div class="body-description">
                                <div class="body-mini-des">
                                    <div class="body-des-title">40 Гб </div>
                                    <div class="body-des">интернета</div>
                                </div>

                                 <div class="body-mini-des">
                                    <div class="body-des-title">15 Гб  </div>
                                    <div class="body-des"><span>на</span> <img src="../assets/ivi.png" alt=""></div>
                                </div>

                                  <div class="body-mini-des">
                                    <div class="body-des-title">40 мин  </div>
                                    <div class="body-des">на звонки вне сети</div>
                                </div>

                                 <div class="body-mini-des">
                                    <div class="body-des-title">2 Гб </div>
                                    <div class="body-des">
                                        <span>на</span>
                                        <img src="../assets/instagram.png" alt="">
                                        <img src="../assets/whatsapp.png" alt="">
                                        <img src="../assets/telegram.png" alt="">
                                    </div>
                                </div>
                            </div>

                            <div class="btn-container">
                                <div class="btn"><span>Подключить</span></div>
                                
                            <div class="btn-des">Получить SIM-карту</div>
                            </div>
                        </div>
                    </div>


            </div>

            <div class="bottom-card">
                  <div class="bottom-card-header">
                      <div class="flex">
                            <img src="../assets/visual (2).png" alt="">
                            <div class="content">
                                <div class="card-header-title">
Подписка ivi еще на 30 дней бесплатно

                                </div>
                                <div class="date">
                                    <span class="date-title">200с</span>
                                    <span class="date-des">/ неделя</span>
                                </div>
                            </div>
                        </div>
                        <div class="content-text">
                            <div class="card-body-title">
                                Активируйте подписку IVI в Мой Beeline
                            </div>
                            <div class="text">
                                еще <span>30 дней</span> бесплатной подписки онлайн-кинотеатра
                            </div>
                        </div>
                        </div>

                        <div class="btn-container-bottom">
                               <div class="btn-des">Получить SIM-карту</div>
                                <div class="btn"><span>Подключить</span></div>
                        </div>
           
            </div>





        </div>

    </div>

</template>


<style scoped>

.btn-container-bottom{
    display: grid;
    grid-template-columns: 1fr 1fr;
    grid-gap: 30px;
    padding: 20px 0;
}
.btn-container-bottom .btn-des{
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
}
.text{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 144%;
/* or 23px */


/* Color/Neutral/6 - Light gray2 */

color: #E8E8E8;
}
.text span{
font-weight: 500;
}
.bottom-card-header {
    display: flex;
    gap: 40px;
    padding: 0 0 20px 0;
    border-bottom: 1px solid #3C2F78;

}
.bottom-card-header .content-text{
    display: flex;
    flex-direction: column;
    gap: 20px;
}
.bottom-card-header .flex{
    display: flex;
    gap: 10px;
}
.bottom-card{
    background: #211943;
border-radius: 16px;
width: 100%;
display: grid;
padding: 25px;
}
.btn-container{
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    flex-direction: column;
    gap: 20px;
}
.btn-des{
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 16px;
line-height: 144%;

display: flex;
align-items: center;
text-align: center;

color: #6C60A9;
}
.btn{
width: 100%;
height: 56px;
/* Color/Primary/1 - Yellow */
background: #FFCD00;
border-radius: 8px;
display: flex;
align-items: center;
justify-content: center;
}
.btn span{
    /* Body 16px 700 bold */

font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 130%;
/* identical to box height, or 21px */

display: flex;
align-items: center;
text-align: center;

/* Color/Neutral/1 - Primary dark */

color: #121212;
}
.body-description{
    padding: 20px 0;
    display: flex;
    flex-direction: column;
    gap: 15px;
}
.body-mini-des{
    font-family: Fira Sans;
font-style: normal;
font-weight: 500;
font-size: 18px;
line-height: 132%;
/* identical to box height, or 24px */
display: flex;
gap: 10px;
align-items: flex-end;
/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.body-des{
    font-weight:400;
font-size: 16px;
line-height: 130%;
display: flex;
gap: 8px;
align-items: flex-end;
}
.card-body{
    padding: 20px 0;
}
.card-body-title{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 16px;
line-height: 144%;
/* identical to box height, or 23px */


color: #EA003D;
}
.card-header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 20px;
    padding: 0 0 20px 0;
 border-bottom: 1px solid #3C2F78;
}
.date{
    display: flex;
    align-items: center;
    gap: 8px;
}
.date-title{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 32px;
line-height: 132%;
/* or 42px */


/* Color/Neutral/7 - White */

color: #FFFFFF;

}
.date-des{
    padding-top: 10px;
    font-family: Fira Sans;
font-style: normal;
font-weight: normal;
font-size: 14px;
line-height: 144%;
/* or 20px */


/* Color/Neutral/6 - Light gray2 */

color: #E8E8E8;
}
.card-header-title{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 18px;
line-height: 132%;
/* identical to box height, or 24px */


/* Color/Neutral/7 - White */

color: #FFFFFF;
}
.cards{
    display: flex;
    gap: 20px;

}
.card{
    background: #211943;
border-radius: 16px;
padding: 25px;
}
.main{
    background: #1A143B;
    display: flex;
    justify-content: center;
}
.container{
    width: 60%;
    display: flex;
    flex-direction: column;
    gap:30px;
}
.title{
    font-family: Fira Sans;
font-style: normal;
font-weight: bold;
font-size: 36px;
line-height: 132%;
/* or 48px */

text-align: center;

/* Color/Neutral/7 - White */

color: #FFFFFF;
}

@media screen and (max-width:1035px) {
    .container{
        width: 90%;
    }
}

@media screen and (max-width:707px) {
    .cards{
        flex-direction: column;
        justify-content: center;
    }
}

@media  (max-width:670px) {
    .bottom-card-header{
        flex-direction: column;
    }
    .btn-container-bottom{
        display: flex;
        flex-direction: column-reverse;
    }
}
</style>