<template>
  <!-- Inizio Counters -->
  <section id="counters">
        <div class="container mt-5">
            <div class="row">
                <div class="col">
                    <img src="@/assets/vector-art-3.png" alt="company foto">                  
                </div>
                <div class="col">
                    <p class="we-are-megaone">We are megaone company</p>
                    <h3>We have done some</h3>
                    <h3>great idea</h3>
                    <p class="counters-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected.</p>

                    <ul class="counter-list list-unstyled">
                        <li class="counter-item">
                            <i aria-hidden="true" class="fas fa-users text-white"></i>
                            <h6 class="counter-number text-white">500 +</h6>
                            <p class="counter-title text-white">Happy Clients</p>
                        </li>
                        <li class="counter-item">
                            <i aria-hidden="true" class="fas fa-list-alt text-white"></i>
                            <h6 class="counter-number text-white">1074 +</h6>
                            <p class="counter-title text-white">Lines Of Code</p>
                        </li>
                        <li class="counter-item">
                            <i aria-hidden="true" class="fas fa-award text-white"></i>
                            <h6 class="counter-number text-white">600 +</h6>
                            <p class="counter-title text-white">Project Completed</p>
                        </li>
                    </ul>
                </div> 
            </div>
        </div>
    </section>
    <!-- Fine Counters -->
</template>

<script>

</script>

<style scoped>
#counters {
    padding: 80px 180px;
    background-color: #03a9f5;
}

#counters h3 {
    font-family: 'Montserrat', sans-serif;
    color: white;
    font-size: 40px;
    position: relative;
}

#counters p {
    font-family: 'Roboto', sans-serif;
    color: white;
    line-height: 30px;
}

#counters .we-are-megaone {
    font-weight: 20px;
    font-size: 20px;
    color: white;
}

.counters-text {
    font-weight:lighter;
}

#counters img {
    width: 100%;
}

.counter-list{
    margin: 0;
    padding-top: 25px;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-wrap: wrap;
    flex-wrap: wrap;
    margin-right: -15px;
    margin-left: -15px;
}

.counter-item{
    position: relative;
    width: 100%;
    padding-right: 15px;
    padding-left: 15px;
    -ms-flex-preferred-size: 0;
    flex-basis: 0;
    -ms-flex-positive: 1;
    flex-grow: 1;
    max-width: 100%;
}

.counter-item i{
    font-size: 36px;
}

.counter-item .counter-number{
    font-size: 32px;
    margin: 5px 0;
}

.counter-item .counter-title{
    font-weight: 400;
    line-height: 1.2;
}
</style>
