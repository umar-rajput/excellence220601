<template>
  <div>
    <div class="min-h-screen flex flex-col">
      <div
        class="flex-grow max-w-7xl mx-auto py-12 px-4 sm:px-6 lg:py-16 lg:px-8"
      >
        <div class="lg:text-center">
          <h2
            class="text-base text-indigo-600 font-semibold tracking-wide uppercase"
          >
            Contact Us
          </h2>
          <p
            class="mt-2 text-3xl leading-8 font-extrabold tracking-tight text-gray-400 sm:text-4xl"
          >
            Get in touch
          </p>
          <p class="mt-4 max-w-2xl text-xl text-gray-300 lg:mx-auto mb-4">
            We would love to hear from you. Please fill out the form below and
            we'll get back to you as soon as possible.
          </p>
        </div>

        <div class="mt-10 sm:mt-0">
          <div class="mt-5 md:mt-0 md:col-span-2">
            <form action="" method="POST">
              <div class="shadow overflow-hidden sm:rounded-md">
                <div class="px-4 py-5 sm:p-6">
                  <div class="grid grid-cols-6 gap-6">
                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="first-name"
                        class="block text-sm font-medium text-gray-200"
                      >
                        First Name
                      </label>
                      <input
                        type="text"
                        name="first-name"
                        id="first-name"
                        class="mt-1 p-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-3">
                      <label
                        for="last-name"
                        class="block text-sm font-medium text-gray-200"
                      >
                        Last Name
                      </label>
                      <input
                        type="text"
                        name="last-name"
                        id="last-name"
                        class="mt-1 p-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-6">
                      <label
                        for="email-address"
                        class="block text-sm font-medium text-gray-200"
                      >
                        Email Address
                      </label>
                      <input
                        type="email"
                        name="email-address"
                        id="email-address"
                        class="mt-1 p-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md"
                      />
                    </div>

                    <div class="col-span-6 sm:col-span-6">
                      <label
                        for="message"
                        class="block text-sm font-medium text-gray-200"
                      >
                        Message
                      </label>
                      <textarea
                        name="message"
                        id="message"
                        rows="4"
                        class="mt-1 p-2 focus:ring-indigo-500 focus:border-indigo-500 block w-full sm:text-sm border-gray-300 rounded-md"
                      ></textarea>
                    </div>
                  </div>
                </div>
                <div class="px-4 py-5 sm:p-6">
                  <button
                    type="submit"
                    class="inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-white font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 sm:text-sm lg:float-right sm:float-left"
                  >
                    Submit
                  </button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script setup>
useHead({
  title: "Contact",
});

definePageMeta({
  layout: "custom",
});
</script>

<style></style>
