<template>
    <main>
        <figure id="jumbo">
            <img src="../assets/img/jumbotron.jpg" alt="">
        </figure>

        <div class="container">
            CONTENTS GO HERE
        </div>
        
    </main>
</template>

<script>
export default {
    
}
</script>

<style lang="scss" scoped>

main {
    background-color: #1C1C1C;
    color: white;
    min-height: 150px;

    #jumbo {
        height: 300px;
        // width: 99vw;

        img {
            object-fit: cover;
            height: 100%;
            object-position: top center;
        }
    }

    .container {
        padding: 10px 0;
    }
}

</style>