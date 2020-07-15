<template>
  <div>
    <Title title="Contact Us"></Title>
    <div class="d-flex justify-content-around flex-wrap">
      <div>
        <Info />
        <Form />
      </div>
    </div>
    <Map />
  </div>
</template>

<script>
import Form from "../components/Contact/Form";
import Map from "../components/Contact/Map";
import Info from "../components/Contact/Info";
import Title from "../components/Shared/PageTitle";

export default {
  name: "Contact",
  components: {
    Form,
    Info,
    Map,
    Title
  }
};
</script>

<style scoped>
.contact {
  padding-bottom: 10px;
  margin-bottom: unset !important;
  background-color: white !important;
  border: none !important;
}
</style>
