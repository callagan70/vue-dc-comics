<template>
        <div class="container">
            <div class="container_list">
                    <!-- NOTE Prima lista -->
                    <div class="container1">
                        <div class="white">DC COMIC</div>
                        <div>
                            <ul>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                            </ul>
                        </div>

                        <div class="white">SHOP</div>
                        
                        <div>
                            <ul>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                            </ul>
                        </div>
                    </div>

                    <!-- NOTE Seconda lista -->
                    <div class="container1">
                        <div class="white">DC</div>
                        <div>
                            <ul>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                            </ul>
                        </div>
                    </div>
                    <!-- NOTE Terza Lista -->
                    <div class="container1">
                        <div class="white">SITES</div>
                        <div>
                            <ul>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                                <li><a href="#">Prova</a></li>
                            </ul>
                        </div>        
                    </div>
            </div>
            
            <div>
                    <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>

            
            
        </div>
</template>

<style scoped lang="scss">

        .container{
            position: absolute;
            z-index: -1;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
            background-image: url('../assets/img/footer-bg.jpg');
            height: 400px;
            width: 100%;
        }

        .container1{
            display: flex;
            flex-direction: column;
            margin: 1em;
        }

        .container_list{
            display: flex;
            flex-wrap: wrap;
            margin-top: 50px;
        }

        .white{
            color: white;
            font-size: 1.2em;
            margin-bottom: 1em;
            margin-top: 1em;
        }

        .container img{
            margin-top: -75px;
        }
        
        .container div>div>ul{
            list-style-type: none;
        }

// FIXME sistemare l'opacità dei caratteri della lista ed il font
        .container div>div>ul li a{
            text-decoration: none;
            color: white;
            opacity: 0.5;
        }
</style>




<script>

export default {
  name: 'SectionThree',
}

</script>
