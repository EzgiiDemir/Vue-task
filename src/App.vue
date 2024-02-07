<template>
  <AppNavbar/>
  <AppMain/>
  <HelloWorld/>
  <AppLink/>
  <AppPrice/>
  <AppLogin/>
  <AppFooter/>
</template>

<script>
import AppNavbar from './components/Navbar.vue';
import AppMain from './components/Main.vue';
import HelloWorld from './components/HelloWorld.vue';
import AppLink from './components/Link.vue';
import AppPrice from './components/Price.vue';
import AppLogin from './components/Login.vue'
import AppFooter from './components/Footer.vue';
export default {
  name: 'App',
  components: {
    AppNavbar,
    AppMain,
    HelloWorld,
    AppLink,
    AppPrice,
    AppLogin,
    AppFooter,

  }
}
</script>


