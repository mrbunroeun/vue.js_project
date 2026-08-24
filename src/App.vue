
<script setup></script>

<template>
  <h1 id="app">You did it!{{name}}</h1>
  <p>
    Visit <a href="https://vuejs.org/" target="_blank" rel="noopener">vuejs.org</a> to read the
    documentation
  </p>

</template>
<script>
  const {createApp, ref} = Vue
  createApp({ 
    setup(){
      const name = ref("Rachel")  
      return {name}
    }
  }).mount("#app")
</script>

<style scoped></style>
