<template>
  <div class="container">
    <img src="../assets/main_logo.png" />
    <b-navbar toggleable="lg">
      <b-navbar-toggle
        target="nav-collapse"
        class="toggle-icon pull-left ms-auto"
      ></b-navbar-toggle>
      <b-collapse class="selection-bar" id="nav-collapse" is-nav>
        <b-navbar-nav>
          <b-nav-item to="/"
            ><span
              class="route"
              :class="currentRoutePath == '/' ? 'active' : ''"
              >Home</span
            ></b-nav-item
          >
          <b-nav-item to="/services"
            ><span
              class="route"
              :class="currentRoutePath == '/services' ? 'active' : ''"
              >Services</span
            ></b-nav-item
          >
          <b-nav-item to="/about"
            ><span
              class="route"
              :class="currentRoutePath == '/about' ? 'active' : ''"
              >About KLAENG</span
            ></b-nav-item
          >
          <b-nav-item to="/contact"
            ><span
              class="route"
              :class="currentRoutePath == '/contact' ? 'active' : ''"
              >Contact</span
            ></b-nav-item
          >
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
  data() {
    return {
      currentRoutePath: "",
    };
  },
  methods: {
    updateCurrentPath() {
      this.currentRoutePath = this.$router.currentRoute.path;
    },
  },
  watch: {
    $route() {
      this.updateCurrentPath();
    },
  },
  created() {
    console.log(this.$router.currentRoute.path);
    this.updateCurrentPath();
  },
};
</script>

<style scoped>
.route {
  color: #000000;
  font-size: 1rem;
  display: flex;
  justify-content: right;
  font-family: "Poppins", sans-serif;
  font-weight: bold;
}
.active {
  color: #655798;
}
.container {
  display: flex;
  justify-content: space-between;
  align-items: top;
}
.b-navbar-toggler {
  right: 15px;
  position: absolute;
}
img {
  width: min(50vw, 200px);
  height: 100%;
}
.selection-bar {
  margin: 10px 0px 0px 0px;
}
.router-link-exact-active {
  color: #655798;
}
</style>