<script>
import Jumbotron from "./Jumbotron.vue"

export default {
  name: 'Header',
  components: {
      Jumbotron
  },
  data(){
    return{
        title: 'Hello Vite',
    }
  }
}

</script>


<template>
  <h1> {{ title }}</h1>
</template>


<style scoped>
h1{
  color: cornflowerblue;
}

</style>