<template>
    <section>
        <div class="container">
            <button id="sign-up"><a href="#">Sign up now!</a></button>

            <ul id="social-icons">
                <li id="social-cta">Follow Us</li>
                <li>
                    <a href="#">
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </a>
                </li>
                <li>
                    <a href="#">
                        <img src="../assets/img/footer-youtube.png" alt="">
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
 background-color: #303030;
}

.container {
    padding: 40px 0;
    display: flex;
    justify-content: space-between;
    align-items: center;

    ul {
        display: flex;
        align-items: center;
        gap: 15px;
        list-style: none;

        #social-cta {
            font-size: 15px;
            color: #0980F4;
            font-weight: 900;
            text-transform: uppercase;
        }

        a {
            display: contents;
        }
    }

    #sign-up {
        padding: 10px 15px;
        border: 2px solid #0282F9;
        background-color: transparent;
        color: white;
        font-weight: 600;
        text-transform: uppercase;

        a {
            color: currentColor;
            text-decoration: none;
        }
    }
}

</style>