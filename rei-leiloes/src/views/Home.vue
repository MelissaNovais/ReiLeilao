<template>
  <div>
    <h1>Home PAGE</h1>
    <h5 @click="$router.push( '/about' )">ABOUT  {{txtGeneric}}</h5>
   
  </div>
</template>

<script>
export default {
  name: "home",
  data(){
    return{
      txtGeneric: 'Oi'
    }
  }

};
</script>

<style scoped>

</style>

