<template>
  <div class="p-4">
    <h1 class="text-5xl">About page</h1>
    <p>
      <NuxtLink to="/" class="text-blue-500 underline">Home page</NuxtLink>
    </p>
  </div>
</template>

<script>
import tailwindConfig from "~tailwind.config";

export default {
  data() {
    return {
      tailwindConfig
    };
  }
};
</script>