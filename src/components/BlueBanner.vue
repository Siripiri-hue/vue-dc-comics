<template>
    <section>
        <div class="container">
            <ul>
                <li>
                    <a href="#">
                        <figure>
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        </figure>
                        <span>Digital Comics</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <figure>
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        </figure>
                        <span>DC Merhandise</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <figure>
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        </figure>
                        <span>Subscription</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <figure>
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        </figure>
                        <span>Comic Shop Locator</span>
                    </a>
                </li>
                <li>
                    <a href="#">
                        <figure>
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        </figure>
                        <span>DC Power Visa</span>
                    </a>
                </li>        
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

section {
    background-color: #0282F9;
}

.container {
    color: white;
    padding: 50px;

    ul {
        display: flex;
        justify-content: space-between;
        align-items: center;

        li {
            display: flex;
            align-items: center;
            gap: 5px;
            font-size: 12px;
            white-space: no-wrap;
            // line-height: 120px;

            a {
                text-decoration: none;
                text-transform: uppercase;
                display: contents;
                color: currentColor;

                figure {
                    height: 60px;
                    width: 60px;

                    img {
                        height: 100%;
                        width: 100%;
                        object-fit: contain;
                    }
                }
            }
        }
    }
}
</style>