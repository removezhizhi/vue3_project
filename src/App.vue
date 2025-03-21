<template>
  <div>
    <h1>Hello World</h1>
    <h2>新增了一个小标题</h2>
  </div>
</template>

<script setup lang="ts" name="app">
const get1 = () => {
  console.log('123')
}

const get2 = () => {
  console.log('123')
}
get1()
get2()
var a = '10'
const str = 'nihao'
console.log(a)
console.log(str)
</script>

<style scoped>
h1 {
  color: red;
}
</style>
