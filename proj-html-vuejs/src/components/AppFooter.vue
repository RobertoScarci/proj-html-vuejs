<template>

    <!-- Footer -->
    <footer class="footer pb-3">    
            <div class="container">
                <div class="row">
                    <div class="col-12">
                        <div class="footer-py-60">
                            <div class="row">
                                <div class="col-lg-4 col-12 mb-0 mb-md-4 pb-0 pb-md-2">
                                    <a href="#" class="logo-footer">
                                        <img src="../assets/logo-light.png" height="24" alt="">
                                    </a>
                                    <p class="mt-4">Start working with Landrick that can provide everything you need to generate awareness, drive traffic, connect.</p>
                                    <ul class="list-unstyled social-icon social mb-0 mt-4">
                                        <li class="list-inline-item mb-0"><a href="" target="_blank" class="rounded"><i class="fa-brands fa-facebook"></i></a></li>
                                        <li class="list-inline-item mb-0"><a href="" target="_blank" class="rounded"><i class="fa-brands fa-instagram"></i></a></li>
                                        <li class="list-inline-item mb-0"><a href="" target="_blank" class="rounded"><i class="fa-brands fa-twitter"></i></a></li>
                                        <li class="list-inline-item mb-0"><a href="" target="_blank" class="rounded"><i class="fa-brands fa-linkedin"></i></a></li>
                                    </ul>
                                </div>
                        
                                <div class="col-lg-2 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                                    <h5 class="footer-head">Company</h5>
                                    <ul class="list-unstyled footer-list mt-4">
                                        <li><i class="fa-solid fa-chevron-right"></i> About us</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Services</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Team</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Pricing</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Project</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Careers</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Blog</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Login</li>
                                    </ul>
                                </div>
                        
                                <div class="col-lg-3 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                                    <h5 class="footer-head">Usefull Links</h5>
                                    <ul class="list-unstyled footer-list mt-4">
                                        <li><i class="fa-solid fa-chevron-right"></i> Terms of Services</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Privacy Policy</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Documentation</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Changelog</li>
                                        <li><i class="fa-solid fa-chevron-right"></i> Components</li>
                                    </ul>
                                </div>
    
                                <div class="col-lg-3 col-md-4 col-12 mt-4 mt-sm-0 pt-2 pt-sm-0">
                                    <h5 class="footer-head">Newsletter</h5>
                                    <p class="mt-4 mb-3">Sign up and receive the latest tips via email.</p>
                                    <form>
                                        <div class="row">
                                            <div class="col-lg-12">
                                                <div class="foot-subscribe mb-3">
                                                    <label class="form-label">Write your email <span class="text-danger">*</span></label>
                                                    <div class="pt-2">
                                                        <input type="email" name="email" id="emailsubscribe" class="section rounded" placeholder="Your email : " required="">
                                                    </div>
                                                </div>
                                            </div>
                                            <div class="col-lg-12">
                                                <div class="d-grid pt-2">
                                                    <input type="submit" id="submitsubscribe" name="send" class="btn btn-soft-primary" value="Subscribe">
                                                </div>
                                            </div>
                                        </div>
                                    </form>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <div class="pt-5">
                <hr>
            </div>

            <!-- footer-bar -->
            <div class="pt-5 footer-bar">
                <div class="container text-center">
                    <div class="row align-items-center">
                        <div class="col-6 start">
                            <p class="">© 2020 Landrick. Design with  <i class="fa-solid fa-heart"></i>by Shreethemes.</p>
                        </div>

                        <div class="col-6">
                            <ul class="list-unstyled text-sm-end mb-0">
                                <li class="list-inline-item"><a href=""><img src="../assets/american-ex.png" class="avatar avatar-ex-sm" title="American Express" alt=""></a></li>
                                <li class="list-inline-item"><a href=""><img src="../assets/discover.png" class="avatar avatar-ex-sm" title="Discover" alt=""></a></li>
                                <li class="list-inline-item"><a href=""><img src="../assets/master-card.png" class="avatar avatar-ex-sm" title="Master Card" alt=""></a></li>
                                <li class="list-inline-item"><a href=""><img src="../assets/paypal.png" class="avatar avatar-ex-sm" title="Paypal" alt=""></a></li>
                                <li class="list-inline-item"><a href=""><img src="../assets/visa.png" class="avatar avatar-ex-sm" title="Visa" alt=""></a></li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </footer>
</template>

<script>
</script>

<style lang="scss" scoped>

@use "../styles/general.scss" as *;
@use "../styles/partials/mixins" as *;
@use "../styles/partials/variables" as *;

.container{
    width: 70%;
}

footer{
    background-color: $footer-color;
    padding-top: 6rem;
}

p,
label,
li{
    color: $text-color;
}

li:hover{
    color: white;
}

li{
    margin: .5rem 0;
}

label{
    font-weight: bold;
    font-size: .8rem;
}

h5{
    color: white;
}

ul li img{
    width: 2.8rem;
}

hr{
    color: grey;
}

input.section{
    background-color: #242e4a;
    border: none;
    font-size: 1rem;
    padding: .6rem;
    width: 100%;
}

div > input{
    color: $text-color;
}

.d-grid input{
    color: $secondary-color;
    background-color: #242e49;
    height: 3.1rem;
}

.d-grid input:hover{
    background-color: $secondary-color;
    color: white;
}

.start{
    display: flex;
    justify-content: flex-start;
}

i{
    margin-right: .5rem;
    padding-bottom: .3rem;
    font-size: .6rem;
}

.fa-heart{
    color: red;
    font-size: 1rem;
}

.social i{
    color: $text-color;
    padding: .3rem;
    font-size: 1.2rem;
    border: .8px solid rgb(156, 156, 156);
    border-radius: 5px;
}

.social i:hover{
    background-color: white;
}

</style>