<template>
  <b-navbar toggleable="lg" type="dark" variant="dark" sticky>
    <b-navbar-brand :to="{ name: 'Home' }">Home</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item :to="{ name: 'About' }">About Us</b-nav-item>
        <b-nav-item :to="{ name: 'Contact' }">Contact Us</b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</template>

<script>
export default {};
</script>

<style scoped>
.navbar {
  font-size: 20px;
}

.bg-dark {
  background-color: rgb(41, 41, 41) !important;
  font-family: "Montserrat", sans-serif;
}
</style>
