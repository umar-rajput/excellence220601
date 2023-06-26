<template>
  <div>
    <div
      class="bg-gray-600 rounded-lg shadow-lg overflow-hidden flex flex-col md:flex-row mx-auto py-4 max-w-5xl mt-3"
    >
      <div class="w-full h-44 md:w-1/3 p-4">
        <img
          src="/images/laptop.jpg"
          alt="Post Image"
          class="w-full h-full object-cover rounded-md"
        />
      </div>
      <div class="w-full md:w-2/3 px-6 py-4">
        <h2 class="text-2xl font-bold mb-2 text-white">
          {{ title }}
        </h2>
        <p class="text-white text-base mb-6">
          {{ truncateDescription(body, 30) }}
        </p>
        <NuxtLink
          :to="'/posts/' + id"
          class="bg-slate-500 hover:bg-slate-700 text-white font-bold py-2 px-4 rounded"
        >
          Read More
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script setup>
// const post = {
//   id: 123,
//   title: "Top 5 freelancing websites",
//   description:
//     "Lorem ipsum dolor sit, amet consectetur adipisicing elit. Saepe fugiat, consequatur dicta minima quia dolor odit? Molestias eos cumque quod!Lorem ipsum dolor sit, amet consectetur adipisicing elit. Est voluptate voluptatibus officia tenetur nihil praesentium similique repudiandae voluptates quo culpa!",
// };

defineProps(["id", "title", "body"]);
function truncateDescription(description, wordsCount) {
  if (description) {
    let words = description.split(" ");
    if (words.length > wordsCount) {
      words = words.slice(0, wordsCount);
      return words.join(" ") + "...";
    }
    return description;
  }
  return "";
}
</script>

<style></style>
