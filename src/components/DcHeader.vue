<template>
    <header>
        <div class="container">
            <figure id="logo">
                <img src="../assets/img/dc-logo.png" alt="">
            </figure>

            <nav>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li class="active"><a href="#">Comics</a></li>
                    <li><a href="#">Movie</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

    .container {
        height: 120px;
        // border-bottom: 1px solid black;
        display: flex;
        justify-content: space-around;
        align-items: center;

        ul {
            list-style: none;
            display: flex;
            gap: 15px;

            li {
                text-transform: uppercase;
                font-size: 12px;
                font-weight: 900;
                line-height: 115px;
                color: #555554;

                a {
                    text-decoration: none;
                }

                &.active::after {
                    content: "";
                    display: block;
                    border-bottom: 4px solid #0282F9;
                }

                &.active {
                    color: #0282F9;
                }
            }
        }
    }

</style>