<template>


 <div>
<navbar/> 
<carusel/>
 </div>
  
</template>

<script>
import navbar from '@/components/navbar';
import carusel from '@/components/carusel';

export default {
  name: 'App',
  components: {
    navbar,
    carusel

  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
