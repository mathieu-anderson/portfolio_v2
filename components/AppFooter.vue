<template>
  <footer>
    <a href="#" v-scroll-to="{ el: '.me', container: 'body', offset: -75 }">Mathieu Anderson</a> |
    <a href="#" v-scroll-to="{ el: '.skills', container: 'body', offset: -55 }">Skills</a> |
    <a href="#"  v-scroll-to="{ el: '.dream', container: 'body', offset: -55 }">Dream</a> |
    <a href="#" v-scroll-to="{ el: '.contact', container: 'body', offset: -55 }">Contact</a> |
    <a href="https://github.com/mathieu-anderson">Github</a> |
    <a href="www.linkedin.com/in/mathieu-anderson">LinkedIn</a> | <a href="#">Email</a>  </footer>
</template>


<style scoped media="screen">
  a
{
  font-weight: normal;
  color: #2B2D42;
  padding-bottom: 0.3rem;
}
  a:hover, a:active
{
  border-bottom: 4px solid
}
</style>
