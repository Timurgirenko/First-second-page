<script setup>
import HeaderBlock from '../Dark/Blocks/HeaderBlock.vue';
import CardBlock from '../Dark/Blocks/CardBlock.vue';
</script>

<template>

    <HeaderBlock />
      <div class="grid_wraper">
        <CardBlock />
        <CardBlock />
        <CardBlock />
        <CardBlock />
        <CardBlock />
        <CardBlock />
        <CardBlock />
        <CardBlock />
      </div>
</template>

<style>
.grid_wraper{
  display: grid;
  grid-template-columns: repeat(4, 368.5px);
  gap: 12px;
}  
</style>
