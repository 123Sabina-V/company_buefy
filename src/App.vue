<template>
  <div class="template">
    <div class="header_bl">
      <Header />
    </div>
      
      <Block1 />
      <Block2 />
      <Block3 />
      <Block5 />
      <Block6 />
      <Block7 />
      <Block8 />
      <Footer />
      <Block9 />
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Block1 from './components/Block1.vue'
import Block2 from './components/Block2.vue'
import Block3 from './components/Block3.vue'
import Block5 from './components/Block5.vue'
import Block6 from './components/Block6.vue'
import Block7 from './components/Block7.vue'
import Block8 from './components/Block8.vue'
import Footer from './components/Footer.vue'
import Block9 from './components/Block9.vue'

export default {
  name: 'App',
  components: {
      Header,
      Block1,
      Block2,
      Block3,
      Block5,
      Block6,
      Block7,
      Block8,
      Footer,
      Block9
      
  },
  
}
</script>

<style>
  #header{
    background-color: #2D2348;
  }
  .template{
    background-color: #2D2348;
  }
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}


</style>
