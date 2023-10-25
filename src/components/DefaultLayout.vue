<template>
  <div class="bg-gray-100 h-full">
    <navBar/>
    <main>
      <router-view/>
    </main>
  </div>
</template>

<script>
import NavBar from "./NavBar.vue";
export default {
  components: { NavBar },
};
</script>

<style></style>
