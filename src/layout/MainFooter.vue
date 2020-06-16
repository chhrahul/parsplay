<template>
    <footer class="footer"
            :class="{[`footer-${type}`]: type}"
            :data-background-color="backgroundColor">
        <div class="container">
            <div class="copyright">
                 Copyright &copy; 
                    {{year}} Pars Play All Rights Reserved.
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
