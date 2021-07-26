<template>
    <div>
        <nav class="navbar">
            <div>
                <img src="../assets/dc-logo.png" alt="">
            </div>
            <ul>
                <li>CHARACTER</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>
            </ul>
        </nav>
    </div>
</template>
<script>
export default {
    name:'header'
}
</script>

<style lang="scss">
    .navbar{
        display: flex;
        justify-content: space-around;
        align-items: center;
    }
    nav ul 
    {
        display: flex;
        list-style-type: none;
    }
    nav ul li 
    {
        padding: 20px 15px;
        border-bottom: 3px solid transparent;
    }
    nav ul li:hover
    {
        border-bottom: 3px solid navy;
    }
</style>