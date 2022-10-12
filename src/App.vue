<template>
  <div id="app">
    <HeaderView />    
    <router-view/>
  </div>
</template>

<script>
  import HeaderView from '@/views/HeaderView.vue';
  export default {    
    name: 'HotPlace',  
    components: { HeaderView }
  }
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  position: absolute;
  top: 0;
  right: 0;
  bottom: 0;
  left: 0;
}
</style>
