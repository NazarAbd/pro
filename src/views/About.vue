<template>
  <div class="about">
    <h1>This is <span> {{name}}</span></h1>
    <h2>His age is <span>{{age}}</span> and he is opsessed with<span>{{opsessed}}</span></h2>
  </div>
</template>
<script>
export default {
  data(){
    return{
      name:'Nazar',
      age:23,
      opsessed:'Front-End Devlopment',
    }
  }
}
</script>
<style scoped>
span{
  color:#42b983
}
</style>
