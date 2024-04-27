<template>
  <!-- Inizio Team -->
  <section class="text-center" id="team">
        <div class="container">
            <!--Row text-->
            <div class="row">
                <div class="col-md-12">
                    <div class="heading-area mx-570 mb-5">
                        <span class="we-are-megaone">We are megaone company</span>
                        <h3 class="title">We have some ideal</h3> 
                        <h3>talented staff</h3>
                        <p class="team-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected.</p>
                    </div>
                </div>
            </div>
            <!--Row team members-->
            <div class="row wow fadeInUp">
                <div class="col-md-4">
                    <div class="team-item">
                        <!--Team Image-->
                        <img alt="image" class="team-image" src="@/assets/team-img1.png">
                        <!--Name-->
                        <div class="name">
                            <img alt="shape" src="@/assets/shape-10.png">
                            <h6>David Joe</h6>
                        </div>
                        <!--Team ruolo-->
                        <p class="ruolo mb-2">Director</p>
                        <!--Team Social-->
                        <div class="team-social social-icon-bg-hvr">
                            <a href="#"><i aria-hidden="true" class="fab fa-facebook-f"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-linkedin-in"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-twitter"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="team-item">
                        <!--Team Image-->
                        <img alt="image" class="team-image" src="@/assets/team-img2.png">
                        <!--Name-->
                        <div class="name">
                            <img alt="shape" src="@/assets/shape-9.png">
                            <h6>Natalie Roy</h6>
                        </div>
                        <!--Team ruolo-->
                        <p class="ruolo mb-2">Director</p>
                        <!--Team Social-->
                        <div class="team-social social-icon-bg-hvr">
                            <a href="#"><i aria-hidden="true" class="fab fa-facebook-f"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-linkedin-in"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-twitter"></i></a>
                        </div>
                    </div>
                </div>
                <div class="col-md-4">
                    <div class="team-item">
                        <!--Team Image-->
                        <img alt="image" class="team-image" src="@/assets/team-img3.png">
                        <!--Name-->
                        <!--Name-->
                        <div class="name">
                            <img alt="shape" src="@/assets/shape-11.png">
                            <h6>Jhon Wok</h6>
                        </div>
                        <!--Team ruolo-->
                        <p class="ruolo mb-2">Director</p>
                        <!--Team Social-->
                        <div class="team-social social-icon-bg-hvr">
                            <a href="#"><i aria-hidden="true" class="fab fa-facebook-f"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-linkedin-in"></i></a>
                            <a href="#"><i aria-hidden="true" class="fab fa-twitter"></i></a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Fine Team -->
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/* Team */
#team {
    padding: 80px 180px;    
}

/* Team Row text */
#team h3 {
    font-family: 'Montserrat', sans-serif;
    color: black;
    font-size: 40px;
    position: relative;
}

#team p {
    font-family: 'Roboto', sans-serif;
    color: black;
    line-height: 30px;
}

#team .we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
    color: black;
}

.team-text {
    font-weight:lighter;
}

/* Team Row team members */
.team-item{
    cursor: pointer;
    position: relative;
}

.team-item .team-image{
    max-width: 250px;
    display: inline-block;
    margin-bottom: 40px;
}

.team-item:hover .team-image{
    -webkit-animation: 1s pulse;
    -o-animation: 1s pulse;
    animation: 1s pulse;
}

.team-item .name{
    position: relative;
}

.team-item .name > h6{
    font-size: 23px;
    margin: 0;
    position: absolute;
    width: 100%;
    top: 50%;
    font-weight: 400;
    transform: translateY(-50%);
    -webkit-transition: all .3s ease-in-out;
    -moz-transition: all .3s ease-in-out;
    -ms-transition: all .3s ease-in-out;
    -o-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
}

.team-item .name > img{
    opacity: 0;
    transition: all .3s ease-in-out;
}

.team-item:hover .name > img{
    opacity: 1;
}

.team-item:hover .name > h6{
    color: #fff;
}

.team-item .team-social a i {
    display: inline-block;
    width: 35px;
    height: 35px;
    text-align: center;
    line-height: 35px;
    border-radius: 50px;
    font-size: 17px;
    margin-right: 1px;
    color: #3b3b3b;
}

.team-item .team-social a i:hover{
    color:#0d60f0;
}
</style>
