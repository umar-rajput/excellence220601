<template>
  <div>
    <div v-if="error" class="text-white">An error occurred...{{ error }}</div>
    <div v-else-if="post">
      <PostDetails
        :id="post.id"
        :title="post.title"
        :body="post.body"
      ></PostDetails>
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
  title: "Post Detail",
});
definePageMeta({
  layout: "custom",
});

const route = useRoute();

const {
  data: post,
  error,
  pending,
} = useLazyFetch(`https://dummyjson.com/post/${route.params.id}`);
// console.log(data);
console.log(post);
</script>

<style></style>
