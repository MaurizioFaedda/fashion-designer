<template>
  <div
    data-aos="fade-down"
    data-aos-easing="linear"
    data-aos-duration="1500"
    class="jumbotron jumbotron-fluid"
  >
    <div class="container">
      <div class="text-right">
        <h1 class="display-4 text-light">Marco Marongiu</h1>
        <p class="lead text-light">Lorem ipsum dolor sit amet</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Jumbotron",
};
</script>
<style lang="scss" scoped>
.jumbotron {
  background-image: url(../../public/img/img_jumbo.jpg);
  background-position: center;
  background-size: cover;
  height: 600px;
}
</style>