<template>
    <div class="List_block">
            <ul class="Ul_list">
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Orbiter Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Scroll Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Track/Scroll</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Orbiter Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Scroll Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Track/Scroll</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Orbiter Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Scroll Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Track/Scroll</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
              <li class="li_item"><button class="Button_item"> <h3 class="li_txt">Orbiter Bridge</h3><div class="Right_txt_button"><h3 class="li_txt">1-3</h3></div></button></li>
            </ul>
          </div>
</template>

<style>
    .List_block{
  width: 282px;
  height: 390px;
  gap: 4px;
}

.Ul_list{
  display: flex;
  flex-direction: column;
  margin: 0px;
  padding: 0px;
  width: 282px;
  height: 390px;
  list-style-type: none;
  overflow-y: scroll;
  gap: 4px;
}

.li_item{
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 282px;
  height: 48px;
}

.Button_item{
  display: flex;
  align-items: center;
  justify-content: space-between;
  width: 282px;
  height: 48px;
  padding: 16px 8px 16px 16px;
  gap: 8px;
  border-radius: 12px;
  border: 0px solid;
  background: #FFFFFF;
  box-shadow: 0px 2px 6px 0px #0000000A;
  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;
  color: #242222;


}

.Right_txt_button{
  width: 32px;
  height: 23px;
  padding: 4px 6px 4px 6px;
  gap: 10px;
  border-radius: 8px;
  background: #F6F6F6;
}

.li_txt{
  margin: 0px;
  font-family: Inter;
  font-size: 12px;
  font-weight: 600;
  line-height: 14.52px;
  color: #737272;
}

</style>