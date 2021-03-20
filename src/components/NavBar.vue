<template>
  <nav class="my-nav navbar navbar-expand-lg fixed-top">
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon text-dark"
        ><i v-if="isHiden" @click="toggleShow" class="fas fa-bars"></i>
        <i v-if="isShowing" @click="toggleShow" class="fas fa-times"></i>
      </span>
    </button>

    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav mx-auto">
        <li
          data-toggle="collapse"
          data-target=".navbar-collapse.show"
          class="nav-item active"
        >
          <a class="nav-link" href="#"
            >Home
            <span class="sr-only">(current)</span>
          </a>
        </li>
        <li
          data-toggle="collapse"
          data-target=".navbar-collapse.show"
          class="nav-item"
        >
          <a class="nav-link" href="#section">Portfolio</a>
        </li>
        <li
          class="nav-item"
          data-toggle="collapse"
          data-target=".navbar-collapse.show"
        >
          <a href="#contacts" class="nav-link">Contacts</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "NavBar",
  data() {
    return {
      isShowing: false,
      isHiden: true,
    };
  },
  methods: {
    toggleShow: function () {
      if (this.isShowing == false) {
        this.isShowing = true;
        this.isHiden = false;
      } else {
        this.isShowing = false;
        this.isHiden = true;
      }
    },
  },
};
</script>
<style lang="scss" scoped>
.my-nav {
  background-color: #fff;
  //   border-bottom: 1px solid rgba(0, 0, 0, 0.4);
  .my-btn {
    color: red !important;
  }
  .nav-link {
    color: rgba(0, 0, 0, 0.6);
    &:hover {
      color: rgba(0, 0, 0, 0.9);
    }
    &::after {
      border-bottom: 1px solid rgba(0, 0, 0, 0.9);
      display: block;
      content: "";
      transform: scaleX(0);
      transition: transform 0.2s linear;
    }
    &:hover::after {
      transform: scaleX(1);
      color: rgba(0, 0, 0, 0.9);
    }
  }
}
</style>