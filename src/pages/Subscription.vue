<template>
    <div class="wrapper pricing">
        <div class="page-header page-header-small">
            <parallax class="page-header-image"
                 style="background-image: url('img/bg37.jpg')">
            </parallax>
            <div class="content-center">
                <div class="row">
                    <div class="col-md-8 ml-auto mr-auto">
                        <h1 class="title">Subscription Plans</h1>
                    </div>
                </div>
            </div>
        </div>
        <div class="main">
         <div class="pricing-4" id="pricing-4">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 ml-auto mr-auto text-center">
                        <h2 class="title">Pick the best plan for you</h2>
                        <h4 class="description">You have Free Unlimited Updates and Premium Support on each
                            package.</h4>
                        <div class="section-space"></div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-4">
                        <card type="pricing" plain>
                            <h6 class="category">Student</h6>
                            <div class="icon icon-danger">
                                <i class="now-ui-icons tech_headphones"></i>
                            </div>
                            <h3 class="card-title">
                                <small>$</small>
                                10
                            </h3>
                            <ul>
                                <li>1000 MB</li>
                                <li>3 email</li>
                                <li>5 Databases</li>
                            </ul>
                            <n-button type="danger" round>Get it Now</n-button>
                        </card>
                    </div>
                    <div class="col-md-4">
                        <card type="pricing" color="orange">
                            <h6 class="category">Standard</h6>
                            <div class="icon icon-primary">
                                <i class="now-ui-icons tech_headphones"></i>
                            </div>
                            <h3 class="card-title">
                                <small>$</small>
                                40
                            </h3>
                            <ul>
                                <li>Unlimited MB</li>
                                <li>Unlimited emails</li>
                                <li>Full Support</li>
                            </ul>
                            <a href="#pablo" class="btn btn-neutral btn-primary btn-round">
                                Get it Now
                            </a>
                        </card>
                    </div>
                    <div class="col-md-4">
                        <card type="pricing" plain>

                            <h6 class="category">Superior</h6>
                            <div class="icon icon-warning">
                                <i class="now-ui-icons tech_headphones"></i>
                            </div>
                            <h3 class="card-title">
                                <small>$</small>
                                20
                            </h3>
                            <ul>
                                <li>1000 MB</li>
                                <li>3 email</li>
                                <li>No Support</li>
                            </ul>
                            <a href="#pablo" class="btn btn-warning btn-round">
                                Get it Now
                            </a>

                        </card>
                    </div>
                </div>
            </div>


        <div class="pricing-2" id="pricing-2">
            <div class="container">
                <div class="row">
                    <div class="col-md-6 ml-auto mr-auto text-center">
                        <h3 class="title">Set up your payment.</h3>
                         <h4 class="description">Your membership starts as soon as you set up payment.
</h4>
                         <h4 class="description">No commitments.<br />Cancel online at any time.
</h4>
                        <div class="section-space"></div>
                    </div>
                </div>
                <div class="row">

                <div class="col-md-2"></div>

                <div class="col-md-4">               
                <!-- PayPal Logo --><table border="0" cellpadding="10" cellspacing="0" align="center"><tr><td align="center"></td></tr><tr><td align="center"><br /><a href="https://www.paypal.com/c2/webapps/mpp/paypal-popup?locale.x=en_C2" title="PayPal Acceptance Mark" onclick="javascript:window.open('https://www.paypal.com/c2/webapps/mpp/paypal-popup?locale.x=en_C2','WIPaypal','toolbar=no, location=no, directories=no, status=no, menubar=no, scrollbars=yes, resizable=yes, width=1060, height=700'); return false;"><img src="https://www.paypalobjects.com/digitalassets/c/website/marketing/apac/C2/logos-buttons/optimize/Full_Online_Tray_RGB.png" border="0" alt="PayPal Acceptance Mark"></a></td></tr></table><!-- PayPal Logo -->
                </div>

                <div class="col-md-4">
            
               <template>
    <VCreditCard @cardChanged="cardChanged"/>
</template>
                    
                </div>

                <div class="col-md-2"></div>


   
                </div>
            </div>
        </div>


        </div>
        </div>
    </div>
</template>
<script>
  import { Card, Button, InfoSection, FormGroupInput, Checkbox } from '@/components';
  import VCreditCard from 'v-credit-card';
  import VCreditCard from 'v-credit-card';
import 'v-credit-card/dist/VCreditCard.css';
  export default {
    data() {
        return {
            name: '',
            cardNumber: '',
            expiration: '',
            security: ''
        };
    },
    name: 'pricing-page',
    bodyClass: 'pricing',
    components: {
      Card,
      InfoSection,
      VCreditCard,
      [Button.name]: Button,
      [Checkbox.name]: Checkbox,
      [FormGroupInput.name]: FormGroupInput
    },
    methods: {
           creditInfoChanged(values) {
            for (const key in values) {
                this[key] = values[key];
            }
        }
    },
  }
</script>
<style>
</style>
