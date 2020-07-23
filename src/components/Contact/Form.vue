<!--<template>-->
<!--  <div>-->
<!--    <div class="d-flex justify-content-center mt-3 mb-3">-->
<!--      <div style="max-width: 600px; min-width: 400px" class="formFill w-10">-->
<!--        <b-form @submit="onSubmit" v-if="show">-->
<!--          <b-form-group id="email-input-group" label="Email address:" label-for="email-input">-->
<!--            <b-form-input-->
<!--              id="email-input"-->
<!--              v-model="form.email"-->
<!--              type="email"-->
<!--              required-->
<!--              placeholder="Enter email"-->
<!--            ></b-form-input>-->
<!--          </b-form-group>-->

<!--          <b-form-group id="name-input-group" label="Your Name:" label-for="name-input">-->
<!--            <b-form-input id="name-input" v-model="form.name" required placeholder="Enter name"></b-form-input>-->
<!--          </b-form-group>-->

<!--          <b-form-group id="number-input-group" label="Your Number:" label-for="number-input">-->
<!--            <b-form-input-->
<!--              id="number-input"-->
<!--              v-model="form.number"-->
<!--              required-->
<!--              placeholder="Enter number"-->
<!--            ></b-form-input>-->
<!--          </b-form-group>-->

<!--          <b-form-group label="Message:" label-for="message-textarea">-->
<!--            <b-form-textarea-->
<!--              id="message-textarea"-->
<!--              v-model="form.message"-->
<!--              placeholder="Send us a message..."-->
<!--              rows="8"-->
<!--              max-rows="6"-->
<!--            ></b-form-textarea>-->
<!--          </b-form-group>-->
<!--          <b-button class="pButton" type="submit" variant="dark">Submit</b-button>-->
<!--        </b-form>-->

<!--        <div>-->
<!--          <b-modal id="modal-center" centered title="Thank you" ok-only>-->
<!--            <p class="notify my-4">We will be in touch shortly.</p>-->
<!--          </b-modal>-->
<!--        </div>-->
<!--      </div>-->
<!--    </div>-->
<!--  </div>-->
<!--</template>-->

<!--<script>-->
<!--import axios from "axios";-->
<!--export default {-->
<!--  data() {-->
<!--    return {-->
<!--      form: {-->
<!--        email: "",-->
<!--        number: "",-->
<!--        name: "",-->
<!--        message: ""-->
<!--      },-->
<!--      show: true-->
<!--    };-->
<!--  },-->
<!--  methods: {-->
<!--    onSubmit(evt) {-->
<!--      evt.preventDefault();-->
<!--      axios-->
<!--        .get(-->
<!--          `https://us-central1-gauntlett-design.cloudfunctions.net/sendMail?dest=contact@eastcentralcountertops.com&email=${this.form.email}&name=${this.form.name}&number=${this.form.number}&message=${this.form.message}`-->
<!--        )-->
<!--        .then(() => {-->
<!--          this.$bvModal.show("modal-center");-->
<!--          this.form = {-->
<!--            email: "",-->
<!--            number: "",-->
<!--            name: "",-->
<!--            message: ""-->
<!--          };-->
<!--        })-->
<!--        .catch(e => {-->
<!--          alert(e);-->
<!--        });-->
<!--    }-->
<!--  }-->
<!--};-->
<!--</script>-->

<!--<style scoped>-->
<!--.pButton:hover {-->
<!--  transition: all 0.2s ease-in-out;-->
<!--  transform: scale(1.1);-->
<!--}-->

<!--.pButton {-->
<!--  opacity: 0.8;-->
<!--  font-family: "Martel", serif;-->
<!--  font-size: 20px;-->
<!--  padding-left: 15px;-->
<!--  padding-right: 15px;-->
<!--}-->

<!--.notify {-->
<!--  font-family: "Martel", serif;-->
<!--  font-size: 20px;-->
<!--  text-align: center;-->
<!--}-->

<!--.b-form {-->
<!--  font-family: "Montserrat", sans-serif !important;-->
<!--}-->

<!--@media only screen and (min-width: 300px) {-->
<!--  .formFill {-->
<!--    min-width: 235px !important;-->
<!--  }-->
<!--}-->

<!--@media only screen and (min-width: 600px) {-->
<!--  .formFill {-->
<!--    min-width: 400px !important;-->
<!--  }-->
<!--}-->
<!--</style>-->
