<template>
  <div >
   <app-header></app-header>
   <app-footer></app-footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Footer from "./components/Footer.vue"
import Dashboard from "./components/Dashboard.vue"
export default {
  components:{
    'app-header': Header,
    'app-footer': Footer,
    'dashboard': Dashboard,
  },
  data () {
    return {
    }
  }
}
</script>

<style>

</style>
