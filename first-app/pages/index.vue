<template>
  <div>
    <div v-if="error">An error occurred...{{ error }}</div>
    <div
      v-else-if="data"
      v-for="{ id, title, body } in data.posts"
      v-bind:key="id"
    >
      <PostCard :id="id" :title="title" :body="body"></PostCard>
    </div>
    <div
      v-else
      class="text-white text-3xl h-screen flex justify-center items-center"
    >
      <span>
        Loading
        <Icon name="eos-icons:bubble-loading" />
      </span>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: "Home",
});
const { data, error, pending } = useLazyFetch(
  "https://dummyjson.com/posts?limit=10"
);
console.log(data);
// console.log(error);
// console.log(pending);
const { data: products } = useFetch("/server/api/porducts.js");
console.log(products);
</script>

<style></style>
