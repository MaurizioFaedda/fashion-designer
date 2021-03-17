<template>
  <div
    data-aos="fade-up"
    data-aos-duration="3000"
    id="contacts"
    class="container-fluid my-5"
  >
    <div class="row py-5">
      <form class="mx-auto w-50 text-left">
        <div class="form-group">
          <label for="name">Name</label>
          <input
            type="text"
            class="form-control"
            id="exampleInputName"
            placeholder="Enter Name"
          />
        </div>
        <div class="form-group">
          <label for="exampleInputEmail1">Email address</label>
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
            placeholder="Enter email"
          />
        </div>
        <div class="form-group">
          <label for="exampleFormControlTextarea1">Example textarea</label>
          <textarea
            class="form-control"
            id="exampleFormControlTextarea1"
            rows="3"
          ></textarea>
        </div>
        <button type="submit" class="btn btn-primary">Submit</button>
      </form>
    </div>
  </div>
</template>
<script>
export default {
  name: "Contacts",
};
</script>
<style lang="sass" scoped>
#contacts
    background-color: #000
</style>
