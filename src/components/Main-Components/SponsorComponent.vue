<template>
    <div>
        <section id="sponsor">
        <div class="container">
            <div class="envato-slider d-flex" id="slider">
                <img src="@/assets/client-4.png" alt="" srcset="">
                <img src="@/assets/client-4.png" alt="" srcset="">
                <img src="@/assets/client-4.png" alt="" srcset="">
                <img src="@/assets/client-4.png" alt="" srcset="">

            </div>
        </div>
        </section>
    </div>

</template>

<script>
export default {
    name:'SponsorComponent',
}
</script>

<style scoped>
#sponsor{
background: linear-gradient(to right, #207efd, #03a9f5);
height: 200px;
padding: 100px 0 360px 0;
}

#sponsor img {
margin-right: 100px;
margin-left: 65px
}
</style>