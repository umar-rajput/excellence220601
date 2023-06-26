<template>
  <div>
    <nav class="bg-gray-800">
      <div class="px-2 sm:px-2 lg:px-8 max-w-7l mx-auto">
        <div class="relative flex items-center justify-between h-16">
          <div class="hidden sm:block sm-ml-6">
            <div class="flex space-x-4">
              <NuxtLink
                to="/"
                class="text-white py-2 px-3 rounded-md text-sm font-medium"
              >
                Home
              </NuxtLink>
              <NuxtLink
                to="/about"
                class="text-gray-300 hover:bg-gray-700 hover:text-white py-2 px-3 rounded-md text-sm font-medium"
              >
                About
              </NuxtLink>
              <NuxtLink
                to="/contact"
                class="text-gray-300 hover:bg-gray-700 hover:text-white py-2 px-3 rounded-md text-sm font-medium"
              >
                Contact
              </NuxtLink>
            </div>
          </div>
        </div>
      </div>
    </nav>
    <!-- <h2>Navbar</h2>
      <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aut eius illo quaerat dolor voluptatum accusantium nesciunt, modi velit officia architecto.</p> -->
  </div>
</template>

<script setup></script>

<style></style>
