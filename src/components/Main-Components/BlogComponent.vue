<template>
    <!-- Inizio Our Blog -->
    <section id="our-blog">
        <div class="container">
            <!-- Blog text -->
            <div class="row text-center">
                <div class="col-md-12">
                    <span class="we-are-megaone">We are megaone company</span>
                    <h2>Our recent news will keep</h2>
                    <h2>everyone updated</h2>
                </div>
            </div>

            <!-- Blog cards -->
            <div class="row blog-card">
                <div class="col-lg-4 card-body">
                    <div class="card" style="width: 18rem;">
                        <img src="@/assets/blog-news-1.jpg" class="card-img-top" alt="blog news 1">
                        <div class="card-body">
                            <p class="date">October 29, 2023</p>
                            <h5 class="card-title">Web design is fun</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit ipsum dolor sit am...</p>
                            <a class="author d-flex align-items-center">
                                <img alt="image" class="author-img bg-blue" src="@/assets/avatar-1.png">
                                <h5 class="author-name">Hena Sword</h5>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 card-body">
                    <div class="card" style="width: 18rem;">
                        <img src="@/assets/blog-news-2.jpg" class="card-img-top" alt="blog news 1">
                        <div class="card-body">
                            <p class="date">October 29, 2023</p>
                            <h5 class="card-title">Future of websites</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit ipsum dolor sit am...</p>
                            <a class="author d-flex align-items-center">
                                <img alt="image" class="author-img bg-blue" src="@/assets/avatar-2.png">
                                <h5 class="author-name">David Villas</h5>
                            </a>
                        </div>
                    </div>
                </div>
                <div class="col-lg-4 card-body">
                    <div class="card" style="width: 18rem;">
                        <img src="@/assets/blog-news-3.jpg" class="card-img-top" alt="blog news 1">
                        <div class="card-body">
                            <p class="date">October 29, 2023</p>
                            <h5 class="card-title">Digital marketing</h5>
                            <p class="card-text">Lorem ipsum dolor sit amet consectetur adipiscing elit ipsum dolor sit am...</p>
                            <a class="author d-flex align-items-center">
                                <img alt="image" class="author-img bg-blue" src="@/assets/avatar-5.png">
                                <h5 class="author-name">Jhon Walker</h5>
                            </a>
                        </div>
                    </div>
                </div>
            </div>   
        </div>
    </section>
    <!-- Fine Our Blog -->
  </template>
  
  
<script>
  
</script>
  
  
<style scoped>
#our-blog {
    padding: 100px 180px;
}

#our-blog h2 {
    font-family: 'Montserrat', sans-serif;
    color: black;
    font-size: 40px;
    position: relative;
}

#team .we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
    color: black;
}


.blog-card {
    position: relative;
    border-radius: 10px;
    overflow: hidden;
    text-align: left;
   
}

.blog-card img{
    width: 100%;
}

.blog-card .card-body{
    padding: 30px;
    background-color: #fff;
}

.blog-card .date{
    color: #f547d8;
}

.blog-card .card-title{
    margin: 10px 0;
    font-weight: 400;
    font-family: 'Montserrat', sans-serif;
}

.blog-card .card-title:hover{
    color: #03a9f5;
}

.blog-card .card-text{
    
    font-weight: lighter;
}

.blog-card .author{
    -ms-flex-align: center;
    align-items: center;
    display: -ms-flexbox;
    display: flex;
    margin-bottom: 10px;
}


.blog-card .author > img{
    max-width: 50px;
    border-radius: 50px;
    overflow: hidden;
    margin-right: 15px;
}

.blog-card .author .author-name{
    font-size: 15px;
    color: black;
    font-family: 'Montserrat', sans-serif;
}

.blog-card .author .author-name:hover{
    color: #03a9f5;  
}
</style>