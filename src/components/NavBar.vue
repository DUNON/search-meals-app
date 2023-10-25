<template>
<header class="bg-white shadow-md h-16 flex justify-between items-stretch">
      <router-link :to="{name:'home'}" class="inline-flex items-center h-full">
        Home
      </router-link>
      <div>
        <router-link :to="{name:'byName'}" class="inline-flex items-center h-full transition-colors px-2 hover:bg-purple-100">
          Search Meals
        </router-link>
        <router-link :to="{name:'byLetter'}" class="inline-flex items-center h-full transition-colors px-2 hover:bg-purple-100">
          Meals by letter
        </router-link>
        <router-link :to="{name:'byIngredient'}" class="inline-flex items-center h-full transition-colors px-2 hover:bg-purple-100">
          Meals by ingredients
        </router-link>
      </div>
    </header>  
</template>

<script>
export default {

}
</script>

<style>

</style>