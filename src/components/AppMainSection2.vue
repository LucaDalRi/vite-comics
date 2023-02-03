<script>

export default {
    name: 'AppMainSection2',
}

</script>

<template>
    <div class="containerSection2">
        <div class="containerIconeLinks">
            <div class="link">
                <img src="../assets/img/buy-comics-digital-comics.png" alt="Comics Digital">
                <span>Digital Comics</span>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-merchandise.png" alt="">
                <span>DC Merchandaise</span>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                <span>Subscription</span>
            </div>
            <div class="link">
                <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                <span>Comic Shop Locator</span>
            </div>
            <div class="link">
                <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                <span>DC Power Visa</span>
            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
.containerSection2 {
    height: 150px;
    background-color: #0282f9;
    color: white;
    display: flex;
    align-items: center;
    justify-content: space-evenly;

    .containerIconeLinks {
        display: flex;
        width: 80%;
        height: 100%;
        font-size: 1.5em;

        :last-child img {
            width: 30%;
        }

        .link {
            display: flex;
            align-items: center;
            width: calc(100% / 5);

            img {
                height: 50%;
                margin-right: 20px;
            }
        }
    }
}
</style>