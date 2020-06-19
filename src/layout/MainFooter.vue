<template>
         <footer class="footer footer-big footer-white">
            <div class="container">
                <div class="content">
                    <div class="row">

                         <div class="col-md-4">
                            <h5>Pars Play</h5>
                            <div class="social-feed">
                                <div class="feed-line">
    
                                    <p>On our website, you’ll find a variety of
Movies, Series, Documentaries,
Anime, and TV Programmes.</p>
                                </div>
                            
                            </div>
                        </div>
                        <div class="col-md-2">
                        <h5>Services</h5>
                            <ul class="links-vertical">
                                <li>
                                    <a href="/subscription#/subscription" class="text-muted">
                                        Subscription
                                    </a>
                                </li>
                                <li>
                                    <a href="#pablo" class="text-muted">
                                        Support
                                    </a>
                                </li>
                            </ul>
                        </div>
                        <div class="col-md-2">
                                <h5>Account</h5>
                                <ul class="links-vertical">
                                    <li>
                                        <a href="#pablo" class="text-muted">
                                            Buy a gift card
                                        </a>
                                    </li>
                                    <li>
                                        <a href="#pablo" class="text-muted">
                                            Buy a gift card
                                        </a>
                                    </li>
                                </ul>
                        </div>
                        <div class="col-md-4">
                            <h5>Follow Us</h5>
                            <ul class="social-buttons">
                                <li>
                                    <a href="#pablo" class="btn btn-icon btn-neutral btn-twitter btn-round">
                                        <i class="fab fa-twitter"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#pablo" class="btn btn-icon btn-neutral btn-facebook btn-round">
                                        <i class="fab fa-facebook-square"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#pablo" class="btn btn-icon btn-neutral btn-dribbble btn-round">
                                        <i class="fab fa-dribbble"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#pablo" class="btn btn-icon btn-neutral btn-google btn-round">
                                        <i class="fab fa-google-plus"></i>
                                    </a>
                                </li>
                                <li>
                                    <a href="#pablo" class="btn btn-icon btn-neutral btn-instagram btn-round">
                                        <i class="fab fa-instagram"></i>
                                    </a>
                                </li>
                            </ul>
                            <h5>
                                <small>Download our Apps</small>
                                <br />
                                <small class="text-muted">App Store | Google Play</small>
                            </h5>
        
                        </div>
                    </div>
                </div>
            </div>
        </footer>
</template>
<script>
  export default {
    props: {
      backgroundColor: String,
      type: String
    },
    data(){
      return {
        year: new Date().getFullYear()
      }
    }
  }
</script>
<style>
.footer:not(.footer-big) .copyright{float: none!important;text-align:center!important;}
</style>
