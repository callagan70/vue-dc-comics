<template>

      <div class="container">
            <div class="container1">
                  <div>
                      <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                  </div>
                  <div>DIGITAL COMIC</div>
            </div>

            <div class="container1">
                  <div>
                      <img src="../assets/img/buy-comics-merchandise.png" alt="">
                  </div>
                  <div>DC MERCHANDISE</div>
            </div>

            <div class="container1">
                  <div>
                      <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                  </div>
                  <div>SUBSCRITION</div>
            </div>

            <div class="container1">
                <div>
                      <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div>COMIC SHOP LOCATOR</div>
            </div>

<!-- FIXME manca l'ultima immagine -->
            
            <div class="container1">
                  <div>
                      <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                  </div>
                  <div>DC POWER VISA</div>     
            </div>
      </div>
</template>

<script>
export default {
  name: 'SectionTwo',
}
</script>



<style scoped lang="scss">

      .container{
            display: flex;
            // position: absolute;
            justify-content: space-around;
            background-color: #0282F9;
            justify-items: center;
            color: white;
            padding: 20px;
            // z-index: 10;
      }

      .container1{
            display: flex;
            flex-wrap: wrap;
            align-items: center;
      }

      .container1 img{
            margin-right: 10px;
      }

</style>