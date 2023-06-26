<template>
  <div>
    <div class="py-16 min-h-screen">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="lg:text-center">
          <h2
            class="text-base text-indigo-600 font-semibold tracking-wide uppercase"
          >
            About Us
          </h2>
          <p
            class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-400 sm:text-4xl"
          >
            Our Story
          </p>
          <p class="mt-4 max-w-4xl text-xl text-gray-400 lg:mx-auto">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Odit
            pariatur adipisci laudantium similique rem nulla sequi, corrupti
            quis dolore! Vel, non. Nulla ipsum consectetur ullam modi assumenda
            similique quibusdam dignissimos.
          </p>
        </div>
        <div class="mt-10">
          <dl
            class="space-y-10 md:space-y-0 md:grid md:grid-cols-2 md:gap-x-8 md:gap-y-10"
          >
            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <Icon class="text-white" name="uil:globe" />
                </div>
              </div>

              <div class="ml-4">
                <dt class="text-lg font-medium text-gray-300 leading-6">
                  Our Mission
                </dt>
                <dd class="mt-2 text-base text-gray-400">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  Officiis voluptas error maiores repellendus maxime cupiditate
                  quas tempora ea quis, necessitatibus officia. Beatae neque
                  eligendi quidem architecto temporibus magni inventore maiores?
                </dd>
              </div>
            </div>

            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <Icon class="text-white" name="uil:arrow-up-left" />
                </div>
              </div>

              <div class="ml-4">
                <dt class="text-lg font-medium text-gray-300 leading-6">
                  Our Mission
                </dt>
                <dd class="mt-2 text-base text-gray-400">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  Officiis voluptas error maiores repellendus maxime cupiditate
                  quas tempora ea quis, necessitatibus officia. Beatae neque
                  eligendi quidem architecto temporibus magni inventore maiores?
                </dd>
              </div>
            </div>

            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <Icon class="text-white" name="uil:lightbulb-alt" />
                </div>
              </div>

              <div class="ml-4">
                <dt class="text-lg font-medium text-gray-300 leading-6">
                  Our Mission
                </dt>
                <dd class="mt-2 text-base text-gray-400">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  Officiis voluptas error maiores repellendus maxime cupiditate
                  quas tempora ea quis, necessitatibus officia. Beatae neque
                  eligendi quidem architecto temporibus magni inventore maiores?
                </dd>
              </div>
            </div>

            <div class="flex">
              <div class="flex-shrink-0">
                <div
                  class="flex items-center justify-center h-12 w-12 rounded-md bg-indigo-500 text-white"
                >
                  <Icon class="text-white" name="uil:analysis" />
                </div>
              </div>

              <div class="ml-4">
                <dt class="text-lg font-medium text-gray-300 leading-6">
                  Our Mission
                </dt>
                <dd class="mt-2 text-base text-gray-400">
                  Lorem ipsum dolor sit amet consectetur, adipisicing elit.
                  Officiis voluptas error maiores repellendus maxime cupiditate
                  quas tempora ea quis, necessitatibus officia. Beatae neque
                  eligendi quidem architecto temporibus magni inventore maiores?
                </dd>
              </div>
            </div>
          </dl>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: "About",
});

definePageMeta({
  layout: "custom",
});
</script>

<style></style>
