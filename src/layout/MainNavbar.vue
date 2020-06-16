<template>
    <navbar position="fixed"
            :transparent="transparent"
            :color-on-scroll="colorOnScroll"
            menu-classes="ml-auto">
        <template slot-scope="{toggle, isToggled}">



        <router-link v-popover:popover1 class="navbar-brand" to="/presentation">
         <img src="img/parsplay_logo.png" width="48"/>
        </router-link>

        </template>
        <template slot="navbar-menu">
            <li class="nav-item">
                <a class="nav-link btn btn-primary"
                   href="http://localhost:8080/login#/login">
                    <p>Login</p>
                </a>
            </li>

        </template>
    </navbar>
</template>

<script>
  import { DropDown, NavbarToggleButton, Navbar, NavLink } from '@/components';
  import { Popover } from 'element-ui'
  export default {
    name: 'main-navbar',
    props: {
      transparent: Boolean,
      colorOnScroll: Number,
    },
    components: {
      DropDown,
      Navbar,
      NavbarToggleButton,
      NavLink,
      [Popover.name]: Popover
    }
  }
</script>

<style scoped>

</style>
