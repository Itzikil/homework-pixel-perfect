
<template>
  <section class="app main-layout">
    <appHeader />
    <appHome />
    <appFooter />
  </section>
</template>

<script>
import appHeader from './components/app-header.vue'
import appFooter from './components/app-footer.vue'
import appHome from './components/app-home.vue'
export default {

  components: {
    appHeader,
    appFooter,
    appHome
  }
}
</script>
