<template>
<div class="container">

        <div class="container1">
            <h3>SIGN-UP NOW!</h3>
        </div>

        <div class="container2">
            <div>
               <h3>FOLLOW US</h3>
            </div>
            <div>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
            </div>
        </div>

</div>
</template>

<style scoped lang="scss">
    .container{
        display: flex;
        justify-content: space-around;
        width: 100%;
        height: 100px;
        margin-top: 400px;
        background-color: #303030;
        align-items: center;
        font-family: Arial, Helvetica, sans-serif;

        .container1{
            color: white;
            padding: 1em;
            border: 2px solid #0282F9;
            width: fit-content;
            height: fit-content;
        }

        .container2{
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            color: #0282F9;
        }
        .container2>div{
            margin-right: 1em;
        }
        .container2>div>img{
            margin-right: 1em;
        }

    }

</style>

<script>
export default {
  name: 'FooTer',
}
</script>