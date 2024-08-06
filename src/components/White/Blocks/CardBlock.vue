<template>
    <div class="card">
          <div class="top_txt">
            <div class="left_block">
              <img src="../../../assets/icons/Money.png" alt="money">
              <h5 class="txt_block">$205M</h5>
            </div>
            <div class="Tier_top_txt">
              <div class="Tier_1"></div>
              <div class="Tier_1"></div>
              <div class="Tier_1"></div>
            </div>
          </div>
          <img class="Bg_card" src="../../../assets/Bg/bg_card.png" alt="Card Background">
          <div class="descriptions">
            <h3 class="Title">Scroll</h3>
            <h4 class="Subtitle">Pizdec project nado brat na vsy kotletu</h4>
          </div>
    </div>
</template>

<style>
.card{
  position: relative;
  display: flex;
  flex-direction: column;
  width: 368.5px;
  height: 292px;
  border-radius: 12px;
  box-shadow: 0px 4px 6px 0px #00000014;
  overflow: hidden;
}

.top_txt{
  position: absolute;
  display: flex;
  justify-content: space-between;
  width: 100%;
  top: 10px;
}

.left_block{
  display: flex;
  align-items: center;
  justify-content: center;
  width: 76px;
  height: 22px;
  gap: 4px;
  border-radius: 6px;
  background: #313132;
  margin-left: 10px;
}

.txt_block{
  font-family: Inter;
  font-size: 12px;
  font-weight: 600;
  line-height: 14.52px;
  color: #FFFFFF;
  margin: 0px;
}

.Tier_top_txt{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 32px;
  height: 22px;
  margin-right: 10px;
  gap: 4px;
  border-radius: 6px;
  background: #313132;
}

.Tier_1{
  width: 4px;
  height: 10px;
  border-radius: 6px;
  background: #6CFF38;
}

.Bg_card{
  width: 368.5px;
  height: 178px;
  border-radius: 16px 16px 0px 0px;
}

.Title{
  font-family: Inter;
  font-size: 20px;
  font-weight: 700;
  line-height: 24.2px;
  margin: 16px 10px 0px 10px;
  color: #313132;

}

.Subtitle{
  width: 336.5px;
  height: 54px;
  font-family: Inter;
  font-size: 15px;
  font-weight: 400;
  line-height: 18.15px;
  margin: 4px 10px 16px 10px;
  color: #31313299;
  display: -webkit-box;
  -webkit-line-clamp: 3;
  -webkit-box-orient: vertical;
  overflow: hidden;
}
</style>