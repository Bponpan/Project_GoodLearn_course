<template>
  <div class="centered-image">
      <img id="img1" src="./assets/img1.png" alt="img">
      <HelloWorld msg=""/>
        
  </div>
  
  
  
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}

</script>

<style>
body{
  max-width: 1440px;
  background-color: rgb(255, 255, 255);
}
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 0; 
  padding-left: 100px;
}
.centered-image{
  text-align: center;
  width: 1360px;
  
}

#img1{
  width:1000px;
  height: auto;
  border-radius: 35px;
}

</style>
