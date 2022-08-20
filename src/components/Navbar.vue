<template>
  <nav
    class="flex items-center justify-around bg-blue-900 py-4 sm:px-32 md:px-32 lg:px-64"
  >
    <h1>
      <router-link to="/" class="text-2xl">Memory Helper</router-link>
    </h1>
    <div class="flex justify-around w-9/12">
      <router-link to="/about">About</router-link>
      <router-link to="/tips">Tips</router-link>
      <router-link to="/yoursubjects">Your Subjects</router-link>
    </div>
    <div></div>
  </nav>
</template>
<script>
export default {};
</script>
<style scoped lang="scss"></style>
