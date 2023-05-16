<template>
  <div class="user">
    <h1>Profile {{ $route.params.id }}</h1>
  </div>
</template>

<script>
export default {
  // Untuk mengambil data user berdasarkan id
  validate({ params }) {
    // Hanya angka
    return /^\d+$/.test(params.id);
  },
};
</script>