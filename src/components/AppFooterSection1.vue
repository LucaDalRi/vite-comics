<script>

export default {
    name: 'AppFooterSection1',
}

</script>

<template>

    <div class="containerFooterSection1">
        <div class="containerLinks">
            <div class="container-DC-Shop">
                <div id="dcComicsLinks">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>Tv</li>
                        <li>Games</li>
                        <li>Video</li>
                        <li>News</li>
                    </ul>
                </div>
                <div id="shopLinks">
                    <h2>SHOP</h2>
                    <ul>
                        <li>Shop DC</li>
                        <li>Shop DC Collectibles</li>
                    </ul>
                </div>
            </div>
            <div class="containerDc">
                <h2>DC</h2>
                <ul>
                    <li>Terms of use</li>
                    <li>Privacy Policy</li>
                    <li>Ad Choises</li>
                    <li>Che sbatti</li>
                    <li>Yes Yes</li>
                    <li>Tanti</li>
                    <li>Bei</li>
                    <li>Links</li>
                    <li>Mamma Mia</li>
                    <li>Pizzeria</li>
                    <li>End</li>
                </ul>
            </div>
            <div class="containerShop">
                <h2>SITE</h2>
                <ul>
                    <li>DC</li>
                    <li>DC Magazine</li>
                    <li>DC</li>
                    <li>DC</li>
                    <li>DC</li>
                </ul>
            </div>
        </div>
    </div>

</template>

<style lang="scss" scoped>
.containerFooterSection1 {
    display: flex;
    align-items: center;
    height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);

    .containerLinks {
        display: flex;
        height: 100%;
        width: 80%;
        padding: 30px;
        margin: 0 auto;
        background-image: url(../assets/img/dc-logo-bg.png);
        background-repeat: no-repeat;
        background-position-x: right;
        background-position-y: center;

        ul {
            list-style: none;
            padding-right: 30px;

            li {
                color: gray;
                line-height: 25px;
            }
        }

        h2 {
            color: white;
            margin: 0 20px 10px 0;
        }

        .container-DC-Shop {
            height: 100%;

            #dcComicsLinks {
                height: 70%;
            }
        }
    }
}
</style>