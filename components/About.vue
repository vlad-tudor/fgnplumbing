<template>
  <div class="about">
    <div style="height: 5rem"></div>
    <h1>About</h1>
    <p>Some personal info here, maybe some photo, location of operation, etc</p>
    <img src="--not--found" alt="my face? idk" />
    <b-row class="info-row">
      <b-col
        ><div class="info-card">
          <h5>Some service</h5>
          <ul class="service-list">
            <li>thing one</li>
            <li>thing two</li>
          </ul>
        </div>
      </b-col>
      <b-col
        ><div class="info-card">
          <div class="info-card">
            <h5>Some other service</h5>
            <ul class="service-list">
              <li>thing one</li>
              <li>thing two</li>
            </ul>
          </div>
        </div></b-col
      >
      <b-col
        ><div class="info-card">
          <div class="info-card">
            <h5>Some service</h5>
            <ul class="service-list">
              <li>thing one</li>
              <li>thing two</li>
            </ul>
          </div>
        </div></b-col
      >
    </b-row>
  </div>
</template>

<script>
export default {
  name: "About",
};
</script>

<style lang="scss" scoper>
.about {
  color: white;
  background-color: coral;
  text-align: center;

  .info-row {
    margin: 1rem;
    margin-bottom: 0;
  }
  .service-list {
    text-align: left;
  }
  // to use info card in other place, move to global styles
  .info-card {
    background-color: rgba(0, 0, 0, 0.1);
  }
}
</style>
