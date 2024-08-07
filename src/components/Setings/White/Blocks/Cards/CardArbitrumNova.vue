<script setup>
/* import ActiveBlock from '../ActiveBlock.vue'; */
import InactiveBlock from '../InactiveBlock.vue';
</script>

<template>
                <div class="Card">
                    <img class="img_info" src="../../../Icons/Info.png" alt="Info">
                    <div class="Card_information">
                        <div class="Card_Walet_block">
                            <div class="Name_card">
                                <img class="card_img" src="../../../Icons/Arbitrum Nova.png" alt="Arbitrum Nova">
                                <h4 class="card_name">Arbitrum Nova</h4>
                            </div>
                            <hr class="card_hr">
                            <h5 class="Wallet">hvj3EHluTHW65KCm5DQbfzegLWTQH4uXzQ8lmKLnflU=</h5>
                        </div>
<!-- <ActiveBlock /> -->
<InactiveBlock />
                    </div>
                </div>
</template>

<style scoped>
.Card{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 695px;
    height: 48px;
    gap: 4px;
    border-radius: 12px;
}

.img_info{
    width: 20px;
    height: 20px;
    margin: 0px;
    padding: 0px;
    cursor: pointer;
}

.Card_information{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 671px;
    height: 48px;
    gap: 16px;
    border-radius: 12px;
    background: #F6F6F6;
}

.Card_Walet_block{
    display: flex;
    align-items: center;
    justify-content: flex-start;
    padding-left: 16px;
    gap: 16px;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
}

.Name_card{
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 4px;
}

.card_img{
    width: 28px;
    height: 28px;
}

.card_name{
    margin: 0px;
    padding: 0px;
    font-family: Inter;
    font-size: 12px;
    font-weight: 700;
    line-height: 14.52px;
    color: #2422225C;
}

.card_hr{
    width: 0px;
    height: 17px;
    border: 1px solid #2422223D;
}

.Wallet{

    margin: 0px;
    padding: 0px;
    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    line-height: 16.94px;
    color: #242222;
}
</style>