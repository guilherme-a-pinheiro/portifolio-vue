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
    background-color: #dccbcb;
  }
   .main {
    height: 100vh;
   }
</style>
