<template>
    <div class="sfondo">
        <div class="footer">
            <span>
                
                <ul>
                    <li><h3>DC COMICS</h3></li>
                    <li>Characters</li>
                    <li>Comics</li>
                    <li>Movies</li>
                    <li>TV</li>
                    <li>Games</li>
                    <li>Videos</li>
                    <li>News</li>
                </ul>
                            <ul>
                    <li><h3>SHOP</h3></li>
                    <li>Shop DC</li>
                    <li>Shop DC Collection</li>
                </ul>

            </span>
            <span>
                
                <ul>
                    <li><h3>DC</h3></li>
                    <li>Term Of Use</li>
                    <li>Privacy</li>
                    <li>Ad Choise</li>
                    <li>Advertising</li>
                    <li>Jobs</li>
                    <li>Subscriptions</li>
                    <li>Talent Workshops</li>
                    <li>CPSC</li>
                    <li>Ratings</li>
                    <li>Shop Help</li>
                    <li>Contact Us</li>
                </ul>
            </span>
            <span>
                <ul>
                    <li><h3>SITES</h3></li>
                    <li>DC</li>
                    <li>MAD Magazine</li>
                    <li>DC Kids</li>
                    <li>DC Universe</li>
                    <li>DC Power Visa</li>

                </ul>
            </span>

        </div>
        <img id="logoBg" src="@/assets/dc-logo-bg.png" alt="" srcset="">
    </div>
</template>
<script>
export default {
    name:'Footer'
}
</script>
<style lang="scss">
    #logoBg{
        float: right;
    }
    .sfondo{
        display: flex;
        justify-content: space-around;
        background-color: rgb(32, 32, 32);
    }

    .footer{
        display: flex;
    }
    .footer ul {
        list-style-type: none;
    }
    .footer ul li 
    {
        color: gray;
    }
    .footer ul li h3 
    {
        color: white;
    }
</style>