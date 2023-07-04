<script setup>

</script>

<template>
  <section class="container mx-auto">
    <h1 class="text-center text-3xl py-12">Class & Style Binding</h1>

    <section class="flex space-x-10">
      <div class="w-1/3 bg-orange-400 h-16"></div>
      <div class="w-1/3 bg-indigo-400 h-16"></div>
      <div class="w-1/3 bg-green-400 h-16"></div>
    </section>

    <section class="mt-10 hidden">
      <div class="bg-red-600 h-16 flex items-center justify-center text-white">
        It's a weekday!
      </div>
    </section>

    <section class="mt-10 hidden">
      <div class="bg-teal-100 border-t-4 border-teal-500 rounded-b text-teal-900 px-4 py-3 shadow-md" role="alert">
        <p class="font-bold">Our privacy policy has changed</p>
        <p class="text-sm">Make sure you know how these changes affect you.</p>
      </div>
    </section>
  </section>
</template>

<style scoped></style>
