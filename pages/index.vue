<template>
  <div class="common-layout">
    我是首页
    <ul>
      <li v-for="item in data" :key="item.id">{{ item.title }}</li>
    </ul>
  </div>
</template>
<script lang="ts" setup>
const { data: dataInfo } = await useFetch(
  "http://jsonplaceholder.typicode.com/posts"
);
const { value } = toRefs(dataInfo);
console.log(value, "value");
</script>
<style lang="scss" scoped>
</style>