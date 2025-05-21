<div class="herobanner"></div>

<div class="smallImageContainer">
    <div class="smallImage"></div>
    <div class="smallImage"></div>
    <div class="smallImage"></div>
</div>

<div class="largeImageContainer">
    <div class="largeImage"></div>
    <div class="largeImage"></div>
</div>

<style>
    .herobanner{
        width: 100%;
        height: 40vh;
        background-color: #333;
    }
    .smallImageContainer, .largeImageContainer{
        max-width: 100%;
        height: 40vh;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
    }
    .smallImage{
        width: 32%;
        height: 100%;
        background-color: #333;
    }
    .largeImage{
        width: 48%;
        height: 100%;
        background-color: #333;
    }
</style>