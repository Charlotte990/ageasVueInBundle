<template>
  <div class="full-width center-content">
    <Header/>
    <Main/>
  </div>
</template>

<script>
import '../assets/app.styl'
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap'
import Header from './components/Header.vue'
import Main from './components/Main.vue'

export default {
  components: {
    Header,
    Main
  }
}
</script>