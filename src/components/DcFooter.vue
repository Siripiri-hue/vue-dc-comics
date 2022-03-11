<template>
    <footer>
        <div class="container">
            <div class="list-col">
                <ul>
                <li class="title">DC Comics</li>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movie</a></li>
                <li><a href="#">Tv</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Collectibles</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">Fans</a></li>
                <li><a href="#">News</a></li>
                <li><a href="#">Shop</a></li>
            </ul>

            <ul>
                <li class="title">Shop</li>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
            </ul>
            </div>    

            <ul class="list-col">
                <li class="title">DC</li>
                <li><a href="#">Term of use</a></li>
                <li><a href="#">Privacy Policy (new)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Jobs</a></li>
                <li><a href="#">Subscription</a></li>
                <li><a href="#">Talent Workshop</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
            </ul>

            <ul class="list-col">
                <li class="title">Sites</li>
                <li><a href="#">DC</a></li>
                <li><a href="#">Mad Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
            </ul>
        </div>
    </footer>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

footer {
    background-image: url("../assets/img/footer-bg.jpg");

    .container {
        padding: 30px 0;
        background-image: url("../assets/img/dc-logo-bg.png");
        background-repeat: no-repeat;
        background-size: 40%;
        background-position: center right;
        display: flex;
        gap: 12px;

        ul {
            list-style: none;
            font-size: 11px;

            li {
                padding: 3px 0;

                &.title {
                    color: white;
                    font-weight: 900;
                    // text-align: center;
                    text-transform: uppercase;
                    font-size: 14px;
                    padding: 7px 0;
                }
                
                a {
                    text-decoration: none;
                    color: #959595;
                }
            }
        }

        
    }

    
}


</style>