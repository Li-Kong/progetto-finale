<template>
   <div>
        <section id="contact">
            <div class="container">
                <div class="row">
                    <div class="col-md-6">
                        <div class="contact-form">
                            <h2>Get in touch</h2>
                            <form action="#" method="post">
                                <div class="form-group">
                                    <input type="text" class="form-control" placeholder="Name" required>
                                </div>
                                <div class="form-group">
                                    <input type="email" class="form-control" placeholder="Email" required>
                                </div>
                                <div class="form-group">
                                    <input type="text" class="form-control" placeholder="Subject" required>
                                </div>
                                <div class="form-group">
                                    <textarea class="form-control" rows="5" placeholder="Message" required></textarea>
                                </div>
                                <button type="button" class="btn btn-primary">Send Message</button>
                            </form>
                        </div>
                    </div>
                    <div class="col location">
                          <h2>Our Location</h2>
                          <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered</p>
                          <div class="contact-detail">
                            <span class="address-icon"><i aria-hidden="true" class="fas fa-map-marker-alt"></i></span>
                            <span class="address-text">123 Park Avenue, New York,United States</span>
                          </div>
                          <div class="contact-detail">
                            <span class="address-icon"><i aria-hidden="true" class="fas fa-phone-volume"></i></span>
                            <span class="address-text">+1 631 1234 5678   +1 631 1234 5678</span>
                          </div>
                          <div class="contact-detail">
                            <span class="address-icon"><i aria-hidden="true" class="fas fa-paper-plane"></i></span>
                            <span class="address-text">email@website.com abc@website.com</span>
                          </div>
                        </div>
                </div>
            </div>
        </section>
    </div>
</template>

<script>

</script>


<style scoped>
#contact {
    padding: 100px 0;
}

#contact h2 {
    font-size: 50px;
    margin-bottom: 40px;
    font-family: 'Montserrat', sans-serif;
}

#contact form .form-control {
    border-radius: 30px;
    border: 1px solid #ccc;
    margin-bottom: 20px;
}

#contact form textarea.form-control {
    height: 150px;
}

#contact form .btn-primary {
    border-radius: 30px;
    padding: 10px 40px;
    font-size: 16px;
    font-weight: bold;
    background-color: #007bff;
    color: #fff;
    border: none;
}

#contact form .btn-primary:hover {
   background-color: #0056b3;
}

#contact .location {
   margin-left: 50px;
}

#contact .location p {
   font-size: 20px;
   font-weight: lighter;
}

#contact .contact-detail {
   padding: 30px 0;
   font-size: 20px;
   font-weight: 100;
}


#contact .address-icon {
   margin-right: 20px;
   color: #1162b8;
}

</style>
