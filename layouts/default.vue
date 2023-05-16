<template>
  <div>
    <header>
      <NuxtLink to="/about">About</NuxtLink>
      <NuxtLink to="/contact">Contact</NuxtLink>
      <NuxtLink to="/user">User</NuxtLink>
    </header>
    <nuxt />
    <footer>
      <p>&Copyright 2023</p>
    </footer>
  </div>
</template>

<style>
body {
  font-family: sans-serif;
  margin: 15%;
  font-size: 16px;
  word-spacing: 1px;
  text-align: center;
}
</style>