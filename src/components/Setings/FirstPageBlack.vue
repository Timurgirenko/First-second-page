<script setup>
import CardTelegramID from './Black/Blocks/Cards/CardTelegramID.vue';
import CardTelegramToken from './Black/Blocks/Cards/CardTelegramToken.vue';
import CardINCH from './Black/Blocks/Cards/CardINCH.vue';
import Card0Swap from './Black/Blocks/Cards/Card0Swap.vue';
import Cardinactive0Swap from './Black/Blocks/Cards/Cardinactive0Swap.vue';
import CardArbitrum from './Black/Blocks/Cards/CardArbitrum.vue';
import CardArbitrumNova from './Black/Blocks/Cards/CardArbitrumNova.vue';
import CardArbitrumNovaOut from './Black/Blocks/Cards/CardArbitrumNovaOut.vue';
import CardNotActive from './Black/Blocks/Cards/CardNotActive.vue';
</script>

<template>
        <div class="Main_bg">
            <header class="Header">
                <button class="Button_header">Telegram API</button>
                <button class="Button_header">API Keys</button>
                <button class="Button_header">RPC</button>
            </header>

            <div class="Container">
                <div class="Walets_wrapper">
                <CardTelegramID/>
                <CardTelegramToken/>
                <CardINCH/>
                <Card0Swap/>
                <Cardinactive0Swap/>
                <CardArbitrum/>
                <CardArbitrumNova/>
                <CardArbitrumNovaOut/>
                <CardNotActive/>

                <CardTelegramID/>
                <CardTelegramToken/>
                <CardINCH/>
                <Card0Swap/>
                <Cardinactive0Swap/>
                <CardArbitrum/>
                <CardArbitrumNova/>
                <CardArbitrumNovaOut/>
                <CardNotActive/>
                <CardTelegramID/>
                <CardTelegramToken/>
                <CardINCH/>
                <Card0Swap/>
                <Cardinactive0Swap/>
                <CardArbitrum/>
                <CardArbitrumNova/>
                <CardArbitrumNovaOut/>
                <CardNotActive/>
            </div>
            </div>
        </div>
</template>

<style>
.Main_bg{
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 1574px;
    height: 909px;
    top: 80px;
    left: 330px;
    padding: 16px 0px 0px 0px;
    margin: 80px 16px 0px 330px;
    gap: 16px;
    border-radius: 16px;
    background: #0E0E0E;
    box-shadow: 0px 0px 8px 0px #0000001F inset;
}

.Header{
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 562px;
    height: 51px;
    gap: 4px;
    border-radius: 16px;
    box-shadow: 0px 4px 6px 0px #00000014;
    background: #171717;
}

.Button_header{
    width: 182px;
    height: 43px;
    gap: 4px;
    border-radius: 8px;
    margin: 0px;
    padding: 0px;

    font-family: Inter;
    font-size: 14px;
    font-weight: 500;
    line-height: 16.94px;
    color: #FFFFFF;
    border: none;
    background: #171717;
    cursor: pointer;
    -webkit-tap-highlight-color: transparent;
}


.Button_header:hover{
    background: #FFFFFF;
    transition: 500ms;
    color: #242222;
}

.Container{
    width: 743px;
    height: 810px;
    padding: 24px;
    border-radius: 16px;
    border: 1px solid #FFFFFF0A;
    box-shadow: 0px 4px 6px 0px #00000014;
    background: #1F2022;
}

.Walets_wrapper{
    display: grid;
    justify-content: center;
    height: 762px;
    gap: 4px;
    grid-template-columns: 695px;
    list-style-type: none;
    overflow-y: scroll;
}

</style>