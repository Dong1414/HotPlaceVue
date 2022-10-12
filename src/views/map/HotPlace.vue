<template>
  <div id="hot">
    <HotMap />
    <Sidebar class="side-bar"/>  
  </div>  
</template>
  
  <script>
  import HotMap from '@/components/HotMap.vue';
  import Sidebar from '@/components/Sidebar.vue';

  export default {    
    name: 'HotPlace',  
    components: { HotMap, Sidebar }
  }
</script>

<style lang="scss">
  #hot {
    position: absolute;
      left: 0;
      top: 50px;
      bottom: 0;
      right: 0;
  }
  #app {    
    .side-bar {
      position: absolute;
      left: 0;
      top: 0;
      bottom: 0;
    }
  }
</style>