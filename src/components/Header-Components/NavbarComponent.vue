<template>
 <!-- Inizio Navbar -->
    <header class="fixed-top">
        <nav class="navbar navbar-expand-lg">
            <div class="container-fluid align-items-center">
                <!-- Logo Navbar -->
                <img src="@/assets/logo-white.png" alt="logo">

                <!-- Navbar Links -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <div class="collapse navbar-collapse" id="navbarSupportedContent">
                    <ul class="navbar-nav me-2 ms-auto mb-2 mb-lg-0">
                        <li class="nav-item nav-major">
                            <a class="nav-link" aria-current="page" href="#jumbotron">Home</a>
                        </li>
                        <li class="nav-item nav-major">
                            <a class="nav-link" href="#about-us">About Us</a>
                        </li>
                        <li class="nav-item nav-major">
                            <a class="nav-link" href="#our-work">Our Work</a>
                        </li>
                        <li class="nav-item nav-major">
                            <a class="nav-link" href="#clients">Clients</a>
                        </li>
                        <li class="nav-item nav-major">
                            <a class="nav-link" href="#our-blog">Our Blog</a>
                        </li>
                        <li class="nav-item nav-major">
                            <a class="nav-link" href="#contact">Contact Us</a>
                        </li>
                    </ul>
                    <button class="btn btn-outline-light border-2 rounded-pill" type="submit">Get A Quote</button>
                </div>

                <!-- Navbar Social -->
                <div class="top-icons">
                    <a href="#" class="social-icon"><i class="fab fa-facebook-f"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-instagram"></i></a>
                    <a href="#" class="social-icon"><i class="fab fa-twitter"></i></a>
                </div>
            </div>
        </nav>
    </header>
    <!-- Fine Navbar -->  
</template>

<script>

</script>


<style scoped>
header {
    background: #3264f5;
    background: -moz-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: -webkit-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: linear-gradient(to right, #3264f5 2%, #7004bc 82%);
    padding: 20px 70px;
}

.nav-link {
    font-family: 'Montserrat', sans-serif;
    color: white;
}

header .nav-major{
    margin: 0 6px;
}

header .nav-major a:hover {
    color: #0dcaf0;
}

header .btn {
    color: white;
}

header .btn:hover {
    background-color: white;
    color: black;
}

.top-icons {
    margin-left: 15px;
}

.social-icon {
    color: white;
    display: inline-block;
    margin: 0 3px;
}

.social-icon:hover {
    color:#0dcaf0;
}
</style>
