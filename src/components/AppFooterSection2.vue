<script>

export default {
    name: 'AppFooterSection2',
}

</script>

<template>

    <div class="containerFooterSection2">

        <div class="containerBtnLinks">
            <div class="containerBtn">
                <button>
                    SING-UP NOW!
                </button>
            </div>
            <div class="containerLinks">
                <div class="containerFollow">
                    <h2>FOLLOW US</h2>
                </div>
                <div class="containerIcone">
                    <div class="icona">
                        <img src="../assets/img/footer-facebook.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="../assets/img/footer-periscope.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="../assets/img/footer-pinterest.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="../assets/img/footer-twitter.png" alt="">
                    </div>
                    <div class="icona">
                        <img src="../assets/img/footer-youtube.png" alt="">
                    </div>
                </div>
            </div>
        </div>

    </div>

</template>

<style lang="scss" scoped>
.containerFooterSection2 {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 150px;
    background-color: #303030;

    .containerBtnLinks {
        width: 80%;
        display: flex;
        height: 70%;

        .containerBtn {
            width: 60%;
            height: 100%;
            display: flex;
            align-items: center;

            button {
                color: white;
                background-color: #303030;
                height: 50%;
                width: 200px;
                border: 2px solid #0a73d4;
                font-size: 1.1em;
            }
        }

        .containerLinks {
            width: 40%;
            display: flex;
            align-items: center;

            .containerFollow {
                color: #0a73d4;
                width: 30%;
            }

            .containerIcone {
                display: flex;
                width: 70%;
                justify-content: space-evenly;
            }
        }
    }
}
</style>