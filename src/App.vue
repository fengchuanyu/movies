<template>
  <div id="app">
    <compo></compo>
    <router-view/>
  </div>
</template>

<script>
import Compo from '@/components/comp/Compo'
export default {
  name: 'App',
  components:{
    Compo
  }
}
</script>

<style>
#app {
  padding-top:1rem;
}
</style>
