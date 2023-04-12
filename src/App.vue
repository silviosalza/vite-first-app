<script>
import AppBanner from "./components/AppBanner.vue"
export default{
  components:{
      AppBanner
    },
  data(){
   
    return{
      title: "MY TITLE"
    }
  }
}
</script>

<template>
  <h1>Hello vue with {{ title }}</h1>
  <AppBanner/>
</template>

<style>
h1{
  color: red;
}
</style>
