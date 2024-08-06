<script setup>
import FirstPage from './components/FirstPage.vue';
/* import SecondPage from './components/SecondPage.vue'; */
</script>

<template>
  <div class="project">
    <div class="in_project">
      <FirstPage /> 
<!--       <SecondPage /> -->
    </div>
  </div>
</template>

<style>


@font-face {
  font-family: "Inter";
  src: url("../src/assets/Fonts/Inter-Regular.ttf");

  
}

.project{
  position: absolute;
  width: 1574px;
  height: 909px;
  top: 80px;
  left: 330px;
  gap: 16px;
  border-radius: 16px;
  padding: 16px;
  background: #F4F6F3;
  box-shadow: 0px 0px 8px 0px #0000001F inset;
}

.in_project{
  position: inherit;
  width: 1542px;
  height: 877px;

  border-radius: 16px;
  background: #FFFFFF;
  padding: 16px 10px 10px 16px;
}

.Main_prod{
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 16px;
}

</style>