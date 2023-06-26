<template>
  <div>
    <div class="max-w-5xl mx-auto overflow-hidden shadow-lg bg-gray-600">
      <img :src="image" alt="" class="object-cover h-96 w-full" />
      <div class="text-white p-6">
        <h1 class="text-2xl font-bold mb-4">{{ title }}</h1>
        <p class="tracking-wide leading-relaxed mb-3">{{ body }}</p>
        <p class="tracking-wide leading-relaxed mb-3">{{ body }}</p>
        <p class="tracking-wide leading-relaxed mb-3">{{ body }}</p>
        <p class="tracking-wide leading-relaxed mb-5">{{ body }}</p>
        <div>
          <span class="font-semibold">Share on : </span>
          <NuxtLink>
            <Icon class="me-2" name="fa6-brands:square-facebook" />
          </NuxtLink>
          <NuxtLink>
            <Icon class="me-2" name="bi:twitter" />
          </NuxtLink>
          <NuxtLink>
            <Icon class="me-2" name="akar-icons:linkedinv1-fill" />
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
// const title = ref("Top 5 freelancing websites.");
// const description = ref(
//   "Lorem ipsum dolor sit amet consectetur adipisicing elit. Magni cupiditate ipsum asperiores illum perferendis possimus harum dolores adipisci reprehenderit aut vitae animi unde, doloremque accusamus rerum delectus, veritatis facere eaque voluptates voluptas? Non impedit vero aspernatur velit! Provident, qui. Eveniet consequuntur sequi, deserunt sit quidem amet. Aut accusamus omnis, dolorem, maiores in similique, ratione explicabo vero veritatis voluptas voluptate nostrum!"
// );
const image = ref("/images/laptop.jpg");
defineProps(["id", "title", "body"]);
</script>

<style scoped></style>
