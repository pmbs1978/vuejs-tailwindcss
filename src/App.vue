<template>
  <header>
    <div class="flex justify-center my-8">
      <nav class="w-4/8 p-4 space-x-2 text-xl text-grey-600">
        <RouterLink to="/" class=" hover:text-green-600">Home</RouterLink>
        <RouterLink to="/about" class=" hover:text-green-600">About</RouterLink>
      </nav>
    </div>
  </header>

  <RouterView />
</template>

<script setup>

</script>

<style>
@import url('./assets/base.css');



.router-link-exact-active {
  color: blue;
}

</style>
