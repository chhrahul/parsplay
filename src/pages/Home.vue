<template>
    <div class="wrapper presentation-page">
      
            <div class="subscribe-line subscribe-line-image" style="background-image: url('img/bg43.jpg')">
                <div class="container">
                    <div class="row">
                        <div class="col-md-6 ml-auto mr-auto">
                            <div class="text-center">
                                <h4 class="title">PARS PLAY</h4>
                                <p class="description">
                                   Unlimited films, Series, Animation, TV programmes and more. Watch anywhere. Cancel at any time!
                                </p>
                            </div>
                            <card type="raised" class="card-form-horizontal">
                                <div class="row">
                                    <div class="col-sm-8">
                                        <fg-input
                                                placeholder="Your Email..."
                                                addon-left-icon="now-ui-icons ui-1_email-85">
                                        </fg-input>
                                    </div>
                                    <div class="col-sm-4">
                                        <n-button type="primary" round block>
                                            Try For Free
                                        </n-button>
                                    </div>
                                </div>
                            </card>
                            <p class="description"> Ready to enjoy? Enter your email to create or restart your subscription.</p>
                        </div>
                    </div>
                </div>
            </div>
  
        <div class="section section-components" data-background-color="dark-red">
            <div class="container">
                <div class="row">
                    <div class="col-md-8 ml-auto mr-auto">
                        <h2 class="text-center title">Watch Everywhere!
                        </h2>
                        <h5 class="text-center description">Stream thousands of popular movies on your phone, tablet, laptop, smart TVs, PlayStation, Xbox, Chromecast and Apple TV without paying

more.</h5>
                        <div class="space-50"></div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-3">
                        <div class="card-container first-card">
                            <div class="card-component">
                                <a href="index.html#basic-elements" target="_blank">
                                    <div class="front">
                                        <img v-lazy="'img/presentation-page/basic_thumb.jpg'" alt="basic_thumb">
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card-container second-card">
                            <div class="card-component">
                                <a href="index.html#cards" target="_blank">
                                    <div class="front">
                                        <img v-lazy="'img/presentation-page/cards_thumb.jpg'" alt="cards_thumb">
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card-container third-card">
                            <div class="card-component">
                                <a href="sections.html" target="_blank">
                                    <div class="front">
                                        <img v-lazy="'img/presentation-page/sections_thumb.jpg'" alt="sections_thumb">
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                    <div class="col-md-3">
                        <div class="card-container fourth-card">
                            <div class="card-component">
                                <a href="examples/product-page.html" target="_blank">
                                    <div class="front">
                                        <img v-lazy="'img/presentation-page/pages2_thumb.jpg'" alt="pages2-thumb">
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="section section-cards">
            <div class="container">
                <div class="row">
                    <div class="col-md-8 text-center ml-auto mr-auto">
                        <div class="section-description">
                            <h2 class="title">All Devices</h2>
                            <h5 class="description">Add such a section for 12 TV channels (It must be 12 sliders, animated)

Description: The right plan starts with a free trial! As a user, you can watch unlimited films, Series, animation and TV programmes at no cost

on Pars TV Channels. Look at the above links and find your desired TV channel.</h5>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-md-12">
                        <div class="images-container">
                            <div class="image-container1">
                                <img v-lazy="'img/presentation-page/card3.jpg'" alt="card 3">
                            </div>
                            <div class="image-container2">
                                <img v-lazy="'img/presentation-page/card6.jpg'" alt="card 6">
                            </div>
                            <div class="image-container3">
                                <img v-lazy="'img/presentation-page/card7.jpg'" alt="card 7">
                            </div>
                            <div class="image-container4">
                                <img v-lazy="'img/presentation-page/card5.jpg'" alt="card 5">
                            </div>
                            <div class="image-container5">
                                <img v-lazy="'img/presentation-page/card4.jpg'" alt="card 4">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="section features-7 section-image" style="background-image: url('img/bg51.jpg')">
            <div class="container-fluid">
                <div class="row">
                    <div class="col-md-6 px-0">
                        <div class="col-sm-12">
                            <info-section title="Save Time & Money"
                                          icon="now-ui-icons business_money-coins"
                                          description="Creating your design from scratch with dedicated designers
                                        can be very expensive.Using PARS PLAY you don't have to worry about
                                        customising the basic Bootstrap 4 design or its components."
                            />

                            <info-section title="Bootstrap 4 & Flexbox"
                                          icon="now-ui-icons text_bold"
                                          description="It is built over Bootstrap 4, it's fully responsive and has
                                        all the benefits of the flexbox for the layout, grid system and components. This
                                        is a huge advantage when you work with columns."
                            />

                            <info-section title="Fast Prototype"
                                          icon="now-ui-icons education_paper"
                                          description="Using PARS PLAY you can create hundreds of components
                                        combinations within seconds and present them to your client. You just need to
                                        change some classes and colors."
                            />
                        </div>
                    </div>
                    <div class="col-md-6">
                        <div class="image-container">
                            <img v-lazy="'img/ipad3.png'" alt="">
                        </div>
                    </div>
                </div>
            </div>
        </div>


    </div>
</template>

<script>
  import { Card, Button, InfoSection, FormGroupInput, Checkbox, Collapse, CollapseItem, Slider } from '@/components';
  import { Carousel, CarouselItem, Tooltip } from 'element-ui'

  export default {
    name: 'presentation',
    bodyClass: 'presentation-page',
    components: {
      Card,
      InfoSection,
      Collapse,
      CollapseItem,
      Slider,
      [Button.name]: Button,
      [Checkbox.name]: Checkbox,
      [FormGroupInput.name]: FormGroupInput,
      [Carousel.name]: Carousel,
      [CarouselItem.name]: CarouselItem,
      [Tooltip.name]: Tooltip,
    },
  }
</script>

<style scoped lang="scss">
    .github-buttons {
        display: flex;
        align-content: center;
    }
    .presentation-page .section-components + .section{z-index: 99999;}
</style>
