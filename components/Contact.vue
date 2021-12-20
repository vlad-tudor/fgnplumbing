<template>
  <div class="contact">
    <div>
      <h3>Contact me</h3>
      <p>I've just copied all this from the vue bootstrap page</p>
      <p>
        here's a good link for reference:
        <a href="https://bootstrap-vue.org/docs/components/form"
          >bootstrap page</a
        >
      </p>
    </div>
    <div class="form-container">
      <b-form>
        <b-form-group
          id="input-group-1"
          label="Email address:"
          label-for="input-1"
          description="We'll never share your email with anyone else."
        >
          <b-form-input
            id="input-1"
            type="email"
            placeholder="Enter email"
            required
          ></b-form-input>
        </b-form-group>

        <b-form-group id="input-group-2" label="Your Name:" label-for="input-2">
          <b-form-input
            id="input-2"
            placeholder="Enter name"
            required
          ></b-form-input>
        </b-form-group>

        <b-button type="submit" variant="primary">Submit</b-button>
        <b-button type="reset" variant="danger">Reset</b-button>
      </b-form>
    </div>
  </div>
</template>

<script>
export default {
  name: "Contact",
};
</script>

<style lang="scss" scoper>
.contact {
  padding-top: 3rem;
  height: 40rem;
  background-color: lightgrey;
  text-align: center;

  .form-container {
    margin: 2rem;
    text-align: left;
    max-width: 30rem;
  }
}
</style>
