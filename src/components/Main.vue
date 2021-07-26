<template>
    <div >
        <div class="add-content">
            <h1> /------- CONTENUTO QUI--------/ </h1>
        </div>
        <ul class="navbar-main">
            <li>
                <img src="@/assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="@/assets/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </li>
            <li>
                <img src="@/assets/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <img src="@/assets/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRIPTIONS</p>
            </li>
            <li>
                <img src="@/assets/buy-dc-power-visa.svg" alt="">
                <p>DC POWER VISA</p>
            </li>



        </ul>
    </div>
</template>
<script>
export default {
    name:'main'
}
</script>
<style lang="scss">
    .add-content{
        background-color: black ;
        padding: 50px 50px;
        color: white;
    }
    .navbar-main
    {
        background-color: cornflowerblue;
        padding: 50px;
        display: flex;
        list-style-type: none;
        justify-content: space-around;
        align-items: stretch;
        margin: 0px;
    }
    .navbar-main li{
        display: flex;
        align-items: center;
    }
    .navbar-main img , .navbar-main svg{
       height: 50px;
       padding-right: 20px;

    }
</style>