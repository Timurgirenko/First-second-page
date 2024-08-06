<template>
          <header class="header_menu">
        <div class="header_left">
          <div class="block_butttons">
            <button class="button_item">All</button>
            <button class="button_item">Tier 1</button>
            <button class="button_item">Tier 2</button>
            <button class="button_item">Tier 3</button>
          </div>

          <select name="" id="" class="selector"> 
            <option class="selector_item" value="">All</option>
            <option class="selector_item" value="">Blockhain</option>
            <option class="selector_item" value="">Bridge</option>
            <option class="selector_item" value="">SocialFi</option>
          </select>
        </div>

        <select name="" id="" class="selector"> 
            <option class="selector_item" value="">Investment</option>
            <option class="selector_item" value="">Tier</option>
            <option class="selector_item" value="">Name (A-Z)</option>
          </select>
      </header>
</template>

<style>
.header_menu{
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 98%;
  margin: 10px 16px 0px 16px;
  padding-bottom: 10px;
  border-bottom: 1px solid #ECECEC;
}

.header_left{
  display: flex;
  align-items: center;
  width: 580px;
  height: 44px;
  gap: 8px;


}

.block_butttons{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 377px;
  height: 44px;
  padding: 4px 0px 0px 0px;
  gap: 4px;
  border-radius: 12px ;
  border: 1px;
  border: 1px solid #EEEAEB;

}

.button_item{
  width: 89.25px;
  height: 36px;
  border-radius: 8px;
  border: none;
  background-color: #FFFFFF;
  color: #2422223B;

  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;

}

.button_item:hover{
  background: #2870DD29;
  color: #2870DD;
  transition: 300ms;
}

.selector{
  width: 195px;
  height: 44px;
  top: 20px;
  left: 20px;
  padding: 6px 12px 6px 12px;
  border-radius: 12px;
  border: 1px;
  border: 1px solid #ECECEC;
}

.selector:hover{
  border: 1px solid #2870DD;
  color: #2870DD;

}

.selector_item{
  width: 187px;
  height: 40px;
  padding: 16px 8px 16px 16px;
  gap: 8px;
  border-radius: 12px;
  background-color: #FFFFFF;

  font-family: Inter;
  font-size: 14px;
  font-weight: 600;
  line-height: 16.94px;
  color: #242222;

}

</style>