<template>
<body class=" bg-white h-[100svh] flex flex-col">
  <Nav/>
  <Sidebar/>
  <home-view/>
  <router-view/>
</body>
   
  
 
</template>
<script>
import Nav from './components/Nav'
import Sidebar from './components/Side-bar.vue'

export default{
  name:'App',
  components:{
    Nav,
    Sidebar
  }
}
</script>

<style>

</style>
