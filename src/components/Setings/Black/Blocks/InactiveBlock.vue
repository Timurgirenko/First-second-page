<template>
    <div class="Activity_block">
        <div class="Circle"></div>
        <h3 class="Inactive">Inactive</h3>
        <button class="button_reload"><img class="Img_reload" src="../IconsBlack/Buttons_reaload.png" alt="Button Reaload"></button>
    </div>
</template>

<style scoped>
.Activity_block{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-right: 16px;
    gap: 4px;
}

.Circle{
    width: 6px;
    height: 6px;
    border-radius: 50%;
    background: #C8C8C8;
}

.Inactive{
    margin: 0px;
    padding: 0px;
    font-family: Inter;
    font-size: 12px;
    font-weight: 600;
    line-height: 14.52px;
    color: #FFFFFF;
}

.button_reload{
    width: 24px;
    height: 24px;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    margin: 0px;
    padding: 0px;
    background: #1B1C1E;
}

.Img_reload{
    width: 24px;
    height: 24px;
}
</style>