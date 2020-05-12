<template>
<body>
  <div id="app">
    <Navbar />
    <Hero/>
    <Table />
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  
  </div>
</body>
</template>

<script>
import Table from './components/Table'
import Hero from './components/Hero'
import Navbar from './components/Navbar'
import HelloWorld from './components/HelloWorld.vue'
// import Menu from './components/Menu'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Navbar,
    Hero,
    Table
  }
}
</script>

<style lang="scss">
@import "~bulma/css/bulma.css"

</style>
