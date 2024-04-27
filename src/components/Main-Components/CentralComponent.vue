<template>
  <!-- Inizio About-us Central -->
  <section id="central">
        <div class="container mt-5">
            <div class="row">
                <div class="col">
                    <p class="we-are-megaone">We are megaone company</p>
                    <h3>Robust Design and</h3>
                    <h3>Development Solutions</h3>
                    <p class="central-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum.</p>
                    <a href="#" class="btn px-4 mt-4 border-2">Learn More</a>
                </div>
                <div class="col">
                    <img src="@/assets/vector-art-4.png" alt="company foto">                  
                </div>
            </div>
        </div>
    </section>
    <!-- Fine About us Central -->
</template>

<script>

</script>

<style scoped>
#central {
    padding: 80px 180px;
    background-color: rgb(245, 247, 247);
}

#central h3 {
    font-family: 'Montserrat', sans-serif;
    color: black;
    font-size: 40px;
    position: relative;
}

#central p {
    font-family: 'Roboto', sans-serif;
    
    color: rgb(63, 61, 61);
    line-height: 30px;
}

.we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
}

.central-text {
    font-weight:lighter;
}

#central a {
    font-family: 'Roboto', sans-serif;
    background-color:#0dcaf0;
    color: white;
    border-radius: 30px;
}

#central a:hover {
    background-color: #f547d8;
}

#central img {
    width: 100%;
}
</style>
