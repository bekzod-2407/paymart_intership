<template>
  <div class="container">
    <navbar></navbar>
    <router-view></router-view>
  </div>
</template>

<script>
import Navbar from '../components/Navbar.vue'
export default {
  components: {
    Navbar,
  }
}
</script>

<style>

</style>