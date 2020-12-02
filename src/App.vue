<template>
  <nav class="navbar sticky-top navbar-light bg-light">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">
        <span style="color:black;">TrueVue</span>
        <span class="icons-wrapper">
          <i class="fab fa-linkedin-in"></i>
          <i class="fab fa-facebook"></i>
          <i class="fas fa-users"></i>
          <i class="fas fa-shopping-bag"></i>
        </span>
      </a>
    </div>
  </nav>
  <div id="nav">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> |
    <router-link to="/gallery">Services</router-link>
  </div>
  <router-view />
</template>

<style lang="scss">
@import "~mdb-ui-kit/css/mdb.min.css";
@import "../src/css/bootstrap-grid.min.css";
@import "../src/css/bootstrap-reboot.min.css";
@import "../src/css/bootstrap-utilities.min.css";
@import "../src/css/bootstrap.min.css";

#app {
  //font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  background-color: #ffffff;
  a {
    font-weight: bold;
    color: #2c3e50;

    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
.icons-wrapper {
  padding-left: 90%;
}
i {
  padding-left: 10px;
  color: rgba(99, 93, 78, 0.719);
}
</style>
