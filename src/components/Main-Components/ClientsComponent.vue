<template>
    <!-- Inizio Clients -->
    <section id="clients">
        <div class="container">
            <div class="row text-center blog-text">
                <div class="col-md-12">
                    <h2>Some great words from our clients</h2>
                    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse tincidunt egestas nunc, at pellentesque arcu sollicitudin et. Aliquam hendrerit diam quis ipsum ultricies, quis ultricies arcu suscipit. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Fusce ut diam quis nulla faucibus venenatis. </p>

                    <h5 class="name gradient-text1">David Villas</h5>
                    <span class="ruolo">Designer, Company Name</span>
                    <ul class="ratings list-unstyled">
                        <li><i aria-hidden="true" class="fas fa-star"></i></li>
                        <li><i aria-hidden="true" class="fas fa-star"></i></li>
                        <li><i aria-hidden="true" class="fas fa-star"></i></li>
                        <li><i aria-hidden="true" class="fas fa-star"></i></li>
                        <li><i aria-hidden="true" class="fas fa-star"></i></li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    <!-- Fine Clients -->
  </template>
  
  
<script>
  
</script>
  
  
<style scoped>
#clients {
    padding: 100px 160px;
    background: #3264f5;
    background: -moz-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: -webkit-linear-gradient(left, #3264f5 2%, #7004bc 82%);
    background: linear-gradient(to right, #3264f5 2%, #7004bc 82%);
    color: white;
    font-family: 'Roboto', sans-serif;
}

#clients h2 {
    padding: 0 180px 30px; 
    font-size: 50px;
}

#clients p {
    padding: 0 150px 30px; 
    font-size: 20px;
    font-weight: lighter;
    font-style: italic;
}

#clients .name { 
    font-size: 30px;
    color: #f547d8;
}

#clients .ruolo { 
    font-size: 15px;
    font-weight: lighter;
}

#clients .ratings{
    margin: 0;
    padding: 0;
    padding-top: 5px;
    display: block;
}

#clients .ratings > li{
    display: inline-block;
    font-size: 13px;
    color: #ffce22;
    line-height: 1;
}
  
</style>