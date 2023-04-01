<template>
  <div class="examples">
    <router-link to="/crud">CRUD</router-link>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "ExamplesView",
};
</script>

<style>
.examples {
  text-align: left;
}
</style>
