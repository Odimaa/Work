<template>
  <div id="app">
    <div ref="myNavi" class="overlay">
      <b-navbar
        class="navbar-custom"
        toggleable="lg"
        type="light"
        variant="light"
        fixed="top"
      >
        <b-navbar-brand href="#">
          <router-link :to="{ name: 'Home' }"
            ><a href="#"> ALLEN</a></router-link
          >
        </b-navbar-brand>

        <b-navbar-toggle @click="openNav()"></b-navbar-toggle>

        <b-collapse id="nav-collapse" is-nav>
          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <b-navbar-nav>
              <a
                href="http://www.linkedin.com/in/odimaa-allen-horsfall-914171131"
                class="btn btn-primary mt-5"
                >Hire Me &rarr;</a
              >

              <!-- <b-nav-item href="#" class="download-btn">GET STARTED</b-nav-item> -->
            </b-navbar-nav>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>

    <div ref="myNav" class="overlay">
      <!-- Button to close the overlay navigation -->
      <a class="closebtn" @click="closeNav()">&times;</a>

      <!-- Overlay content -->
      <div class="overlay-content">
        <a href="#"><router-link :to="{ name: 'Home' }">Home</router-link></a>
        <a
          href="http://www.linkedin.com/in/odimaa-allen-horsfall-914171131"
          class="btn btn-primary mt-5"
          >Hire Me &rarr;</a
        >
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "nav",
  methods: {
    closeNav() {
      /* Close when someone clicks on the "x" symbol inside the overlay */
      this.$refs.myNav.style.width = "0%";
    },
    openNav() {
      /* Open when someone clicks on the span element */
      this.$refs.myNav.style.width = "100%";
      this.$refs.myNavi.style.width = "0%";
    },
  },
};
</script>

<style scoped>
/*--------------------------------------------------------------
# Navbar
--------------------------------------------------------------*/
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Reggae+One&display=swap");

.nav-item.nav-item.nav-item a {
  padding: 5px 10px 0px 0px;
  font-size: 15px;
  color: #2c318d;
}

a {
  color: #222;
  transition: all 0.3s ease;
  text-decoration: none;
  font-family: "Reggae One", cursive;
}

a:hover {
  text-decoration: none;
}
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Reggae One", cursive;
  color: #162746;
}
p {
  font-family: "Reggae One", cursive;
  font-size: 14px;
  line-height: 24px;
}
.navbar-custom {
  padding-bottom: 30px;
}

.navbar-brand a {
  padding: 5px 10px 0px 0px;
  font-size: 15px;
  color: #2c318d;
}

@media (max-width: 768px) {
  .nav-item.nav-item.nav-item a {
    font-size: 20px;
    margin-left: 8%;
  }

  .download-btn_2 {
    margin-top: 10px;
    padding-right: 50px;
    margin-left: 15%;
    text-align: center;
  }
}

@media (max-width: 568px) {
  .navbar-brand img {
    padding-left: 0px;
    padding-top: 5px;
  }

  .nav-item.nav-item.nav-item a {
    margin-left: 20%;
  }
  .download-btn_2 {
    margin-top: 10px;
    padding-right: 50px;
    margin-left: 16%;
    margin-right: 12%;
    text-align: center;
  }
}

.overlay {
  height: 100%;
  width: 0;
  position: fixed;
  z-index: 1;
  left: 0;
  top: 0;
  background-color: rgb(0, 0, 0);
  background-color: rgba(0, 0, 0, 0.9);
  overflow-x: hidden;
  transition: 0.5s;
}

.overlay-content {
  position: relative;
  top: 25%;
  width: 100%;
  text-align: center;
  margin-top: 30px;
}

.overlay a {
  padding: 8px;
  text-decoration: none;
  font-size: 20px;
  color: black;
  display: block;
  transition: 0.3s;
}

.overlay a:hover,
.overlay a:focus {
  color: #f1f1f1;
}

.overlay .closebtn {
  position: absolute;
  top: 20px;
  font-size: 60px;
  right: 45px;
}

@media screen and (max-height: 450px) {
  .overlay a {
    font-size: 20px;
  }
  .overlay .closebtn {
    font-size: 40px;
    top: 15px;

    right: 35px;
  }
}

.btn {
  padding: 13.5px 36px;
  font-weight: 700;
  border-radius: 30px;
  font-size: 13px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.btn-primary {
  background-color: #6264fa;
}
.btn-primary:hover {
  background-color: #3b3dd1;
}
</style> 