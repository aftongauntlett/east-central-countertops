<template>
  <div>
    <b-button
      class="aboutButton mx-2 mb-5"
      variant="dark"
      v-for="link in links"
      :key="link.link"
      :to="{ name: link.link }"
      >{{ link.name }}</b-button
    >
  </div>
</template>

<script>
export default {
  data() {
    return {
      links: [{ name: "Learn more", link: "About" }],
    };
  },
};
</script>

<style scoped>
.aboutButton:hover {
  transition: all 0.2s ease-in-out;
  transform: scale(1.1);
}

.aboutButton {
  opacity: 0.8;
  font-size: 20px;
}
</style>
