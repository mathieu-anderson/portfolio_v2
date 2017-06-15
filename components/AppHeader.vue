<template>
  <header>
    <a href="#" v-scroll-to="{ el: '.me', container: 'body', offset: -75 }">Me</a> |
    <a href="#" v-scroll-to="{ el: '.skills', container: 'body', offset: -55 }">Skills</a> |
    <a href="#"  v-scroll-to="{ el: '.dream', container: 'body', offset: -55 }">Projects</a> |
    <a href="#" v-scroll-to="{ el: '.contact', container: 'body', offset: -55 }">Contact</a> |
    <a href="https://github.com/mathieu-anderson">Github</a> |
    <a href="https://www.linkedin.com/in/mathieuanderson">LinkedIn</a> | <a href="#">Email</a>
  </header>
</template>

<script type="text/javascript">
// import VueLoop from 'vue-loop'
import VueScrollTo from 'vue-scrollto'
export default {
  components: {
    // VueLoop
    VueScrollTo
  }
}
</script>

<style scoped media="screen">
  a {
  font-weight: normal;
  color: #2B2D42;
  }
  a:hover, a:active {
    border-bottom: 4px solid
  }
</style>
