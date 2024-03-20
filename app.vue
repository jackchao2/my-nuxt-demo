<template>
  <div>
    <!-- <NuxtWelcome /> -->
    <!-- <NuxtPage /> -->

    <NuxtLayout> <NuxtPage /> </NuxtLayout>

    <!-- <NuxtWelcome /> -->
    <!-- <Cart />
    <button @click="handleClick">测试点击</button>
    {{ dataInfo }} -->
    <!-- hello nuxt -->
  </div>
</template>
<script lang="ts" setup>
// let data = reactive({} as any);
// const handleClick = async () => {
//   console.log("点击了");
//   const data = await useFetch("http://jsonplaceholder.typicode.com/posts");
//   // console.log(data.data.value, "data");
//   let dataInfo = toRefs(data.data);
//   console.log(dataInfo, "dataInfo");
//   // data = dataInfo?.value;
//   // console.log(dataInfo.value, "data");
// };
</script>
<style lang="scss" >
html,
body {
  padding: 0;
  margin: 0;
}
</style>
