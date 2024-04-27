<template>
  <!-- Inizio Jumbotron -->
  <div id="jumbotron">
        <div class="container py-3">
            <div class="row">
                <!-- Inizio jumbotron animation -->
                <div class="col">
                    <img src="@/assets/vector-art-1.png" class="img-fluid animated" alt="Megaone foto">
                </div>
                <!-- Fine jumbotron animation -->

                <!-- Inizio jumbotron text -->
                <div class="col d-flex align-items-center">
                    <section class="jumbotron-text">
                        <h1 class="text-capitalize jumbotron-title-1">
                            <strong>Creative</strong>
                        </h1>
                        <h1 class="text-capitalize">
                            <strong>Digital Agency</strong>
                        </h1>
                        <p>Lorem ipsum is simply dummy text of the printing and typesetting. Lorem Ipsum has been the industry's standard dummy. Lorem Ipsum has been the industry's standard dummy. </p>
                        <div class="jumbotron-icons d-flex align-items-center">
                            <button type="button" class="btn rounded-pill">
                                <a href="#" class="text-decoration-none">Learn More</a>
                            </button>
                        </div>
                    </section>
                </div>
                <!-- Fine jumbotron text -->
            </div>

            <!-- Inizio Scroll down -->
            <div class="row text-center" id="scroll-down">
                <a href="#about-us">Scroll down ↓</a>
            </div>  
            <!-- Fine Scroll down -->
        </div>
    </div>
    <!-- Fine Jumbotron -->

</template>


<script>

</script>


<style scoped>
#jumbotron {
    margin-top: 96px;
    padding: 40px 160px 0;
    background: #3264f5;
    background: -moz-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: -webkit-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: linear-gradient(to right, #3264f5 2%, #7004bc 82%);
    color: white;
    font-family: 'Roboto', sans-serif;
}

/* jumbotron text */
.jumbotron-text h1{
    font-size: 60px;
    font-family: 'Montserrat'; 
}

.jumbotron-title-1 {
    color: rgb(243, 65, 208);
}

.jumbotron-text p {
    font-size: 17px;
    font-weight: 300;
    margin: 40px 0;
    line-height: 30px;
}

.jumbotron-text .btn {
    background-color: #0dcaf0;
    padding: 8px 25px;
    font-weight: 300;
    font-size: 17px;
}

.jumbotron-text .btn a {
    color: white;
}

.jumbotron-text .btn:hover {
    background-color: white;
}

.jumbotron-text .btn a:hover {
    color: black;
}


/* Jumbotron animation */
#jumbotron img {
    width: 65%;
}

.animated {
    animation: move-up-down 2s ease-in-out infinite alternate-reverse;
}

@keyframes move-up-down {
    0% {transform: translateX(20px);}
    100% {transform: translateX(-20px);}
}

/* Scrow down */
#jumbotron #scroll-down {
    margin: 140px 0 10px;
}

#jumbotron #scroll-down a {
    color:white;
    text-decoration: none;
}

</style>