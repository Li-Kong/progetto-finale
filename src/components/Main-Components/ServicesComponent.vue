<template>
  <!-- Inizio Services list-->
  <section id="services">
        <div class="container">
            <div class="row">
                <div class="col-md-3">
                    <div class="service-component">
                        <span class="service-icon blue"><i aria-hidden="true" class="fas fa-folder-open"></i></span>
                        <h4 class="service-heading">World leader in consulting and finance</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="service-component">
                        <span class="service-icon midnight"><i aria-hidden="true" class="fas fa-code"></i></span>
                        <h4 class="service-heading">A focused team with a specialized skill</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="service-component">
                        <span class="service-icon purple"><i aria-hidden="true" class="fas fa-cog"></i></span>
                        <h4 class="service-heading">Trusted and professional advisors for you</h4>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="service-component">
                        <span class="service-icon pink"><i aria-hidden="true" class="fas fa-edit"></i></span>
                        <h4 class="service-heading">Experience to give you a better results</h4>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Fine Services list-->
</template>

<script>

</script>

<style scoped>
#services {
    padding: 80px 180px;
}


.service-component {
    text-align: center;
    cursor: pointer;
}

.service-component > .service-heading{
    font-size: 17px;
    line-height: 1.5;
    font-weight: 400;
    margin-top: 20px;
}

.service-component > .service-icon {
    position: relative;
    z-index: 1;
}

.service-component > .service-icon {
    display: inline-block;
    height: 90px;
    width: 90px;
    line-height: 90px;
    font-size: 28px;
    font-weight: 600;
    color: #fff;
    text-align: center;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    -webkit-transition: all .3s ease;
    -o-transition: all .3s ease;
    transition: all .3s ease;
}

.service-component:hover > .service-icon::before {
    content: "";
    background: transparent;
    top: 1px;
    left: 1px;
    bottom: 1px;
    right: 1px;
    position: absolute;
    -webkit-border-radius: 50%;
    border-radius: 50%;
    border: 4px solid #fff;
    -webkit-transition: all .3s ease-in-out;
    -moz-transition: all .3s ease-in-out;
    -ms-transition: all .3s ease-in-out;
    -o-transition: all .3s ease-in-out;
    transition: all .3s ease-in-out;
}


.service-component > .service-icon.blue{
    background: #03a9f5;
}

.service-component:hover .service-icon.blue{
    -webkit-animation: itg_pulse_blue 1s infinite;
    -o-animation: itg_pulse_blue 1s infinite;
    animation: itg_pulse_blue 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(0, 188, 212);
    box-shadow:0 0 0 0 rgb(0, 188, 212);
}

.service-component > .service-icon.midnight{
    background: #41526b;
}

.service-component:hover .service-icon.midnight{
    -webkit-animation: itg_pulse_midnight 1s infinite;
    -o-animation: itg_pulse_midnight 1s infinite;
    animation: itg_pulse_midnight 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(65, 82, 107);
    box-shadow:0 0 0 0 rgb(65, 82, 107);
}

.service-component > .service-icon.purple{
    background: #9556f5;
}

.service-component:hover .service-icon.purple{
    -webkit-animation: itg_pulse_purple 1s infinite;
    -o-animation: itg_pulse_purple 1s infinite;
    animation: itg_pulse_purple 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(149, 86, 245);
    box-shadow:0 0 0 0 rgb(149, 86, 245);
}

.service-component > .service-icon.pink{
    background: #f021b6;
}

.service-component:hover .service-icon.pink{
    -webkit-animation: itg_pulse_pink 1s infinite;
    -o-animation: itg_pulse_pink 1s infinite;
    animation: itg_pulse_pink 1s infinite;
    -webkit-box-shadow:0 0 0 0 rgb(240, 33, 182);
    box-shadow:0 0 0 0 rgb(240, 33, 182);
}

</style>
