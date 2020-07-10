<template>
  <b-navbar toggleable="lg" type="light" variant="light" sticky>
    <b-navbar-brand :to="{ name: 'Home' }">Home</b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item :to="{ name: 'About' }">About Us</b-nav-item>
        <b-nav-item :to="{ name: 'Portfolio' }">View our Work</b-nav-item>
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
</style>
