<template>
  <div class="container mx-auto px-20 flex space-x-10 mt-5">
    <div class="flex flex-col items-start">
      <div class="rounded-full px-4 font-black text-green-500 bg-green-100">  In Progress </div>
      <div class="text-2xl font-bold mt-4 mb-4">The Accredited Sales Executive (ASE) End-point app</div>
      <div class="rounded bg-green-500 py-2 px-5 font-bold text-white">ADD UPDATE</div>
    </div>
    <div class="flex flex-row items-start space-x-2">
      <Box title="Due Date" description="12/02/21" />
      <Box title="Ammount (USD)" description="$250,000.00" />
    </div>
  </div>
</template>

<script>
import Box from './Box.vue'
export default {
  name: 'Account',
  components: {
    Box
  }
}
</script>

<style scoped lang="css">
.customized {
  background: #d9efd5;
  color: #3ead2c;
}
</style>

