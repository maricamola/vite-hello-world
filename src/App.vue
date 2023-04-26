<script>
import Header from "./components/Header.vue"
import Jumbotron from "@/components/Jumbotron.vue"

export default {
  name: 'App',
  components:{
    Header,
    Jumbotron
  },
  data(){
    return{
      title: "Hello Vite!"
    }
  }
}
</script>

<template>
  <Header/>
  <h1>{{ title }}</h1>
  <Jumbotron/>
</template>

<style scoped>
h1{
  color: crimson;
}
</style>