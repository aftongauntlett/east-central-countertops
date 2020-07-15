<template>
  <div class="d-flex justify-content-center pb-3">
    <b-card no-body class="overflow-hidden" style="max-width: 540px;">
      <b-card-body title="Email">
        <b-card-text>
          <a href="mailto:contact@eastcentralcountertops.com">contact@eastcentralcountertops.com</a>
        </b-card-text>
      </b-card-body>
      <b-card-body title="Phone">
        <b-card-text>+1 320 679 8288</b-card-text>
      </b-card-body>
      <b-card-body title="Address">
        <b-card-text>
          1814 220th Ave
          <br />Mora, MN 55051
        </b-card-text>
      </b-card-body>
    </b-card>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
a {
  color: rgb(0, 119, 255);
  -o-transition: 0.5s;
  -ms-transition: 0.5s;
  -moz-transition: 0.5s;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

a:hover {
  color: rgb(52, 57, 63);
}

.card {
  border: unset !important;
  font-family: "Montserrat", sans-serif;
}
</style>
