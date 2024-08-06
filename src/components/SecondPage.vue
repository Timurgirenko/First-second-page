<script setup>
import ScrollList from './ScrollList.vue';
</script>

<template>
<div class="Main_prod">
    <div class="about_prod">
          <div>
            <button class="Button_back"><img class="arrow_left" src="../assets/icons/Arrow Left.png" alt="arrow left"><h4 class="Txt_button">Back</h4></button>
            <div class="Header_prod">
              About Project
            </div>

            <hr class="hr_1">

            <div class="Main_info">
              <div class="logo_block">
                <img class="logo" src="../assets/icons/Scroll.png" alt="Scroll">
                  <div class="social_media">
                    <img class="img_globe" src="../assets/icons/Globe-1.png" alt="Globe">
                    <img class="img_discord" src="../assets/icons/Discord.png" alt="Discord">
                    <img class="img_twiter" src="../assets/icons/twiter.png" alt="Twiter">
                  </div>
              </div>
              <h4 class="description_scroll">Scroll - это сеть L2, построенная на Ethereum, а если быть точнее, «накопительный проект с нулевым разглашением». Проект довольно интересный, на уровне ZkSync, может даже имеет спрос выше него. Но как ни крути, Scroll будет дороже всех своих сотоварищей и особенным, так как не базируется на OP – стеке.</h4>
            </div>
          </div>


            <hr class="hr">

            <div class="tags">
              <div class="tags_1">
                <div class="taglist">
                    <img class="" src="../assets/icons/Tier 1.png" alt="Tier-1">
                      <div class="descr_tags">
                        <h3 class="h3_tag">Tier <br> 1</h3>
                      </div>
                </div>
                  <div class="taglist">
                    <img class="img_tags" src="../assets/icons/Globe-2.png" alt="Globe-2">
                      <div class="descr_tags">
                        <h3 class="h3_tag">Type Project</h3>
                        <span class="span_tag">Blockchain</span>
                      </div>
                  </div>
                  <div class="taglist">
                    <img class="img_tags" src="../assets/icons/Money_blue.png" alt="Money_blue">
                      <div class="descr_tags">
                        <h3 class="h3_tag">Total Invest</h3>
                        <span  class="span_tag">$ 205M</span>
                      </div>
                  </div>
              </div>
              
              <div class="invrstors_tag">
                  <img class="img_tags" src="../assets/icons/Investors.png" alt="Investors">
                    <div class="descr_tags">
                      <h3 class="h3_tag">Investors</h3>
                      <span class="span_tag">Paradigm, Binance, Coinbase</span>
                    </div>
              </div>
            </div>

            <hr class="hr">

            <div class="think">
              <h1 class="title">Мысли по выносу</h1>
              <h2 class="subtitle">Активируем кошельки (делаем первые транзакции), затем ждем scroll квесты, ориентировочно они пройдут с мая по октябрь 2024. Советую пополнять кошельки на 0.02+ ETH через официальный мост</h2>
            </div>
        </div>

        <div class="list_scroll">
          <h1 class="Title_module">Modules</h1>
          <hr class="hr_list_scroll">
            <ScrollList />
        </div>
</div>
</template>

<style>
    .about_prod{
  position: relative;
  display: flex;
  flex-direction: column;
  width: 642px;
  height: 499px;
  padding: 24px;
  gap: 24px;
  border-radius: 16px;
  box-shadow: 0px 4px 6px 0px #00000014;

}

.Button_back{
  position: absolute;
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 82px;
  height: 36px;
  margin-bottom: 10px;
  padding: 8px 12px 8px 12px;
  gap: 4px;
  border-radius: 12px;
  border: 1px solid #2870DD;
  transition: 300ms;
}

.arrow_left{
  width: 20px;
  height: 20px;
}

.Txt_button{
  margin: 0px;
  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;
  color: #2870DD;
}

.Header_prod{
  text-align: center;
  font-family: Inter;
  font-size: 24px;
  font-weight: 700;
  line-height: 29.05px;
  color: #242222;
  margin-bottom: 16px;
}

.hr_1{
  width: 594px;
  height: 0px;
  border: 1px 0px 0px 0px;
  border: 1px solid #ECECEC;
  margin: 0px;
}

.hr{
  width: 594px;
  height: 0px;
  border: 1px 0px 0px 0px;
  border: 1px solid #ECECEC;

}

.Main_info{
  display: flex;
  gap: 16px;
  width: 594px;
  height: 102px;
  margin-top: 16px;
}

.logo_block{
  display: flex;
  flex-direction: column;
  align-items: center;
  width: 158px;
  height: 101px;
  gap: 10px;
}

.logo{
  width: 158px;
  height: 55px;
}

.social_media{
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 124px;
  height: 36px;
  gap: 8px;
}

.description_scroll{
  margin: 0px;
  font-family: Inter;
  font-size: 14px;
  font-weight: 500;
  line-height: 16.94px;
  color: #242222;

}

.tags_1{
  display: flex;
  align-items: center;
  justify-content: space-around;
  width: 594px;
  height: 36px;
  gap: 16px;


}

.taglist{
  display: flex;
  align-items: center;
  width: 187.33px;
  height: 36px;
  gap: 8px;

}

.img_tags{
  width: 36px;
  height: 36px;
}

.descr_tags{
  display: flex;
  flex-direction: column;
}

.h3_tag{
  margin: 0px;
  font-family: Inter;
  font-size: 14px;
  font-weight: 500;
  line-height: 16.94px;
  color: #2422227A;
}

.span_tag{
  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;
  color: #242222;
}

.invrstors_tag{
  display: flex;
  gap: 16px;
  width: 594px;
  margin-top: 24px;
}

.think{
  width: 594px;
  height: 96px;
  padding: 12px 16px 12px 16px;
  gap: 4px;
  border-radius: 16px;
  border: 0px 0px 1px 0px;
  background: #FFF8DE;
}

.title{
  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;
  color: #242222;
}

.subtitle{
  font-family: Inter;
  font-size: 14px;
  font-weight: 500;
  line-height: 16.94px;
  color: #242222;
}

.list_scroll{
  display: flex;
  flex-direction: column;
  width: 330px;
  height: 499px;
  padding: 24px;
  gap: 16px;
  border-radius: 16px;
  box-shadow: 0px 4px 6px 0px #00000014;
}

.Title_module{
  margin: 0px;
  font-family: Inter;
  font-size: 24px;
  font-weight: 700;
  line-height: 29.05px;
  color: #242222;
}

.hr_list_scroll{
  margin: 0px;
  width: 282px;
  height: 0px;
  border: 1px solid #ECECEC;
}


</style>