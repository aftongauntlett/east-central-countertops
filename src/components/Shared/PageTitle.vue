<template>
  <div>
    <h2>{{title}}</h2>
    <hr class="my-4" />
  </div>
</template>

<script>
export default {
  props: ["title"]
};
</script>

<style scoped>
h2 {
  font-size: 40px;
  color: rgb(26, 104, 26);
  font-family: "Montserrat", sans-serif;
}
</style>