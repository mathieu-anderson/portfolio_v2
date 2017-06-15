<template>
  <div>
    <AppHeader v-show="top" />
    <a name="start"></a>
    <nuxt/>
    <AppFooter v-show="bottom" />
  </div>
</template>

<script>
import AppHeader from '~components/AppHeader.vue'
import AppFooter from '~components/AppFooter.vue'

export default {
  components: {
    AppHeader,
    AppFooter
  },
  data () {
    return {
      top: true,
      bottom: false
    }
  },
  methods: {
    isMobile: function () {
      if (window.screen.width > 450) {
        console.log('triggered')
        this.top = true
        this.bottom = false
      } else {
        this.top = false
        this.bottom = true
      }
    }
  },
  beforeMount () {
    this.isMobile()
  }
}
</script>

<style>
.container
{
  padding-top: 4rem;
  width: 100%;
  text-align: center;
}

.title
{
  color: #505153;
  font-weight: 300;
  font-size: 2.5rem;
  margin: 0;
}
</style>
