<template>
  <div id="app">
    <Welcome/>
    <Cards/>
    <Application/>
    <About/>
    <FooterTMP/>
  </div>
</template>

<script>
import Welcome from './components/welcome.vue'
import Cards from './components/Cards.vue'
import Application from './components/application.vue'
import About from './components/About.vue'
import FooterTMP from './components/footer.vue'
export default {
  name: 'App',
  components: {
    Welcome,
    Cards,
    Application,
    About,
    FooterTMP
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Fira+Sans&display=swap');
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

</style>
