<template>
  <div>
    <HomePage />
    <SobreMim />
    <MySkills />
    <MeuContato />
  </div>
</template>

<script>
import HomePage from './components/HomePage.vue';
import SobreMim from './components/SobreMim.vue';
import MySkills from './components/MySkills.vue';
import MeuContato from './components/MeuContato.vue';

export default {

  name: 'App',
  components: {
    HomePage,
    SobreMim,
    MeuContato,
    MySkills
  }
}
</script>

<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
    background-color: #ecd3d3;
  }
   .main {
    height: 100vh;
    border-bottom: 5px solid #000;
   }
</style>
