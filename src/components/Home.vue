<template>
  <MainNavbar />
  <div class="main text-center" style="margin: 9% 0">
    <MainCounter />
  </div>
  <MainFooter />
</template>

<script>
import MainNavbar from './elements/Navbar.vue'
import MainCounter from './elements/Counter.vue'
import MainFooter from './elements/Footer.vue'
export default {
  name: 'MainHome',
  components: {
    MainNavbar,
    MainCounter,
    MainFooter
  }
}
</script>
