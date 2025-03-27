<script setup>

import SubmitButton from './components/SubmitButton.vue';

</script>



<!------------Html------------>



<template>


<div>
<h1> Hello, World!</h1>
<SubmitButton>Submit</SubmitButton>
  
</div>
  
</template>



<!------------Scss------------>




<style lang="scss" scoped>
$cor-primaria: #42b983;

.container {
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
}

h1 {
  color: $cor-primaria;
  text-align: center;
}
</style>