<template>
  <div>
    <section>
        <div class="lower-main-adjustments">
            <div class="container">
                <div class="cards">
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        </div>
                        <div class="card-text">
                            <span>DIGITAL COMICS</span>
                        </div>
                    </div>
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        </div>
                        <div class="card-text">
                            <span>DC MERCHANDISE</span>
                        </div>
                    </div>
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        </div>
                        <div class="card-text">
                            <span>SUBSCRIPTION</span>
                        </div>
                    </div>
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        </div>
                        <div class="card-text">
                            <span>COMIC SHOP LOCATOR</span>
                        </div>
                    </div>
                    <div class="card">
                        <div class="card-image">
                            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        </div>
                        <div class="card-text">
                            <span>DC POWER VISA</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
  </div>
  
</template>

<script>
export default {
    name: "MyCards",
}
</script>

<style scoped lang="scss">
    @import "../style/variables.scss";
    @import '../style/common.scss';
    .lower-main-adjustments{
        padding: 3rem 4rem;
        background-color: $brand_main_color;
        color: white;
    }
    .cards{
        height: 100px;
        display: flex;
        justify-content: space-between;
    }
    .card{
        display: flex;
        align-items: center;
    }
    .card-image{
        display: inline-block;
        height: 40px;
    }
    .card-text{
        margin-left: 10px;
    }
</style>