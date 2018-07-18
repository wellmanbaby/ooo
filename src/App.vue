<template>
  <div id="app">
    <leftbar></leftbar>
    <div class="main">
      <router-view/>
    </div>
    

  </div>
</template>

<script>
import leftbar from '@/components/commen/leftbar'
export default {
  name: 'App',
  components:{
    leftbar
  }
}
</script>

<style>
#app {
  font-family: 'Microsoft YaHei','Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: left;
  color: #2c3e50;
   height:100%;
}
.main{
  float:left;
  width:95%; 
  background-color: #EFF2F7;
  height:100%;
  overflow: auto;
 
}
</style>
