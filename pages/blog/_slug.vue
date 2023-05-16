<template>
  <div class="slug">
    <main v-if="$route.params.slug">
      <h1 v-text="'Blog ' + $route.params.slug"></h1>
    </main>
    <main v-else>
      <h1>List Blog</h1>
    </main>
  </div>
</template>