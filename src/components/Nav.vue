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
          <b-nav-item href="#"
            ><span class="route active">Home</span></b-nav-item
          >
          <b-nav-item href="#"><span class="route">Services</span></b-nav-item>
          <b-nav-item href="#"
            ><span class="route">About Klaeng</span></b-nav-item
          >
          <b-nav-item href="#"><span class="route">Contact</span></b-nav-item>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {};
</script>

<style>
.route {
  color: black;
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
</style>