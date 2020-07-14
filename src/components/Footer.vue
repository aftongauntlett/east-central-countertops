<template>
  <div>
    <div class="contactInfo">
      <div class="fontStyle d-flex justify-content-center flex-column">
        <div class="companyName">
          <b>EAST CENTRAL COUNTERTOPS</b>
        </div>
        <div class="solid-border align-self-center"></div>
        <p>
          1814 220th Ave
          <br />Mora, MN 55051
        </p>
        <div>Phone: +1 320 679 8288</div>
        <div>
          Email:
          <a
            href="mailto:contact@eastcentralcountertops.com"
          >contact@eastcentralcountertops.com</a>
        </div>
        <div>
          Website:
          <a
            href="http://www.eastcentralcountertops.com"
          >http://www.eastcentralcountertops.com</a>
        </div>
      </div>
      <div class="footerFont">
        &copy; Copyright 2020 |
        <span style="color: white">East Central Countertops</span> | All Rights Reserved
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footerFont {
  padding-top: 30px;
  padding-bottom: 20px;
  color: rgba(214, 214, 214, 0.692);
  border-top: 2px solid rgba(151, 151, 151, 0.445);
  margin-top: 40px;
}

.companyName {
  padding-bottom: 20px;
  font-size: 25px;
  color: white !important;
}

.contactInfo {
  padding-top: 20px;
  background-color: rgb(41, 41, 41);
}

.fontStyle {
  text-align: center;
  color: rgba(214, 214, 214, 0.692);
  margin-top: 40px;
}

.solid-border {
  border: 1px solid rgb(235, 235, 235);
  width: 5%;
  margin-top: 1%;
  margin-bottom: 2%;
  text-align: center;
}

a {
  color: rgb(255, 196, 0);
  -o-transition: 0.5s;
  -ms-transition: 0.5s;
  -moz-transition: 0.5s;
  -webkit-transition: 0.5s;
  transition: 0.5s;
}

a:hover {
  color: rgb(255, 145, 0);
}
</style>
