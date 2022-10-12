<template>
  <div class="main">
   <div class="placeSch">
      <input type="text" name="placeSch" id="placeSch" />
      <button >검색</button>
   </div>
   <div class="nowLocalSch">
      <router-link to="/hotPlace">현재 위치에서 검색</router-link>
      <!-- <button @click="fnNowLocalSch">현재 위치에서 검색</button> -->
      
   </div> 
  </div>
</template>

<script>

export default {
  name: 'HomeView',
  methods:{
    fnNowLocalSch: function(){
      
    }
  },
}

</script>

<style>
  .main{
    background-image: url('../assets/mainView.png');
    width:100%;
    height: 100vh;
    background-size: cover;
  }
</style>
