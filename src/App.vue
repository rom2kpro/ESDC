<template>
  <div id="app">
    <Header/>
    <Slide/>
    <ListItems/>
    <TourHomePage/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/header/index.vue'
import Slide from './components/slide/index.vue'
import Footer from './components/footer/index.vue'
import ListItems from "./components/list-items/index.vue"
import TourHomePage from "./components/tourincountry-homepage/index.vue"
export default {
  name: 'App',
  components: {
    Header,
    Slide,
    Footer,
    ListItems,
    TourHomePage
  }
}
</script>

<style>
*{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
}
</style>
