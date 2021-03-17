<template>
  <div
    data-aos="fade-up"
    data-aos-duration="3000"
    class="jumbotron jumbotron-fluid"
  >
    <div class="container">
      <div>
        <h1 class="display-4 text-light">Marco Marongiu</h1>
        <p class="lead text-light">
          This is a modified jumbotron that occupies the entire horizontal space
          of its parent.
        </p>
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