<template>
  <the-header />
  <main>
    <the-aside />
    <router-view/>
  </main>
</template>

<script>
import TheAside from '@/ui/TheAside'
import TheHeader from '@/ui/TheHeader'

export default {
  name: 'App',
  components: {
    TheAside,
    TheHeader
  }
}
</script>

<style lang="scss">
  @import "@/assets/styles/normalize";
  @import "@/assets/styles/basics";
</style>
