<template>
  <div id="section" class="container">
    <div id="section-content" class="row py-5">
      <div class="row-content">
        <div data-aos="fade-up" data-aos-duration="3000" class="col-md-6">
          <img class="img-fluid grow" src="img/img_section_1.jpg" alt="" />
        </div>
        <div
          data-aos="fade-up"
          data-aos-duration="3000"
          class="col-md-6 d-flex align-items-center"
        >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, est
          tempore. Nesciunt omnis ducimus quo illo accusamus unde, officia
          accusantium aperiam. Impedit dicta repudiandae beatae iure culpa quia?
          Facere, saepe.
        </div>
      </div>
      <div class="row-content">
        <div data-aos="fade-up" data-aos-duration="3000" class="col-md-6">
          <img class="img-fluid grow" src="img/img_section_2.jpg" alt="" />
        </div>
        <div
          data-aos="fade-up"
          data-aos-duration="3000"
          class="col-md-6 d-flex align-items-center"
        >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, est
          tempore. Nesciunt omnis ducimus quo illo accusamus unde, officia
          accusantium aperiam. Impedit dicta repudiandae beatae iure culpa quia?
          Facere, saepe.
        </div>
      </div>
      <div class="row-content">
        <div data-aos="fade-up" data-aos-duration="3000" class="col-md-6">
          <img class="img-fluid grow" src="img/img_section_1.jpg" alt="" />
        </div>
        <div
          data-aos="fade-up"
          data-aos-duration="3000"
          class="col-md-6 d-flex align-items-center"
        >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, est
          tempore. Nesciunt omnis ducimus quo illo accusamus unde, officia
          accusantium aperiam. Impedit dicta repudiandae beatae iure culpa quia?
          Facere, saepe.
        </div>
      </div>
      <div class="row-content">
        <div data-aos="fade-up" data-aos-duration="3000" class="col-md-6">
          <img class="img-fluid grow" src="img/img_section_2.jpg" alt="" />
        </div>
        <div
          data-aos="fade-up"
          data-aos-duration="3000"
          class="col-md-6 d-flex align-items-center"
        >
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Tenetur, est
          tempore. Nesciunt omnis ducimus quo illo accusamus unde, officia
          accusantium aperiam. Impedit dicta repudiandae beatae iure culpa quia?
          Facere, saepe.
        </div>
      </div>
    </div>
  </div>
</template>
<style lang="sass" scoped>
.grow
  transition: all .9s ease-in-out
  &:hover
    transform: scale(1.02)
.row-content
  display: flex
  &:nth-child(odd)
    flex-direction: row-reverse
  & > :first-child
    padding: 0
    margin-bottom: 16px

@media screen and (max-width: 768px)
  .row-content, .row-content:nth-child(odd)
    flex-direction: column
    margin: 14px 0
</style>