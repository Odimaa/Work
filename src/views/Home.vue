<template>
  <div class="home py-5">
    <section id="parallax">
      <div class="container">
        <div class="row" style="height: 800px">
          <div class="col-12 d-flex align-items-center">
            <div class="text-center w-100">
              <div class="tt mb-4"><img src="images/potrait.png" /></div>
              <h1 class="display-5 weight-600">Hi, I'm Odimaa Allen</h1>
              <h6 class="mb-4">FullStack Developer</h6>

              <a href="images/CV.pdf" class="btn btn-primary mt-5"
                >Download CV &rarr;</a
              >
            </div>
          </div>
        </div>
      </div>
    </section>
    <div class="bg-new-3 py-5">
      <div class="container py-5">
        <h2 class="h1 font-weight-bold mb-3 text-center">Skillset</h2>

        <div class="row align-items-center py-5">
          <div class="col-md-12 col-lg-4">
            <div class="bb shadow-sm"><i class="lni lni-code"></i></div>
            <div class="p-5 shadow-sm border-radius-new bg-white">
              <h4 class="font-weight-bold mb-3">Web Development</h4>
              <p class="m-0"></p>
            </div>
          </div>
          <div class="col-md-12 col-lg-8">
            <div class="row">
              <div class="col-6">
                <div class="bg-new p-5 text-white">
                  <h4 class="bg-heading">#Development</h4>
                  <ul class="list-unstyled uu">
                    <li>HTML</li>
                    <li>CSS</li>
                    <li>Javascript</li>
                    <li>Java</li>
                    <li>PHP</li>
                  </ul>
                  <br />
                  <h4 class="bg-heading">#Frameworks</h4>
                  <ul class="list-unstyled uu">
                    <li>Vue.js</li>
                    <li>React</li>
                    <li>Laravel</li>
                  </ul>
                </div>
              </div>
              <div class="col-6">
                <div class="bg-new-2 p-5 text-white">
                  <h4 class="bg-heading2">#Dev Tools</h4>
                  <ul class="list-unstyled uu">
                    <li>Visual Studio Code</li>
                    <li>Bootstrap</li>
                    <li>Tailwind</li>
                    <li>Figma</li>

                    <li>Eclipse</li>
                    <li>Github</li>
                    <li>Gitlab</li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>

      <section class="section site-portfolio">
        <h2 class="h1 font-weight-bold mb-3 mt-3 text-center">Portfolio</h2>

        <div class="container">
          <div class="row mb-5 align-items-center">
            <div
              class="col-md-12 col-lg-6 mb-4 mb-lg-0"
              data-aos="fade-up"
            ></div>
            <div
              class="col-md-12 col-lg-6 text-left text-lg-right"
              data-aos="fade-up"
              data-aos-delay="100"
            >
              <!-- <div id="filters" class="filters">
              <a href="#" data-filter="*" class="active">All</a>
              <a href="#" data-filter=".web">Web</a>
              <a href="#" data-filter=".design">Design</a>
              <a href="#" data-filter=".branding">Branding</a>
              <a href="#" data-filter=".photography">Photography</a>
            </div> -->
            </div>
          </div>
          <div
            id="portfolio-grid"
            class="row no-gutter"
            data-aos="fade-up"
            data-aos-delay="200"
          >
            <div class="item web col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/cushion" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>Consulatation Company</h3>
                  <span>Landing page</span>
                </div>
                <img class="img-fluid" src="images/consult.jpg" />
              </router-link>
            </div>
            <div class="item photography col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/Digital" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>Digital Agency</h3>
                  <span>Landing page</span>
                </div>
                <img class="img-fluid" src="images/noir.jpg" />
              </router-link>
            </div>
            <div class="item branding col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/Restaurant" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>Restaurant</h3>
                  <span>Home</span>
                </div>
                <img class="img-fluid" src="images/restaurant.jpg" />
              </router-link>
            </div>
            <div class="item design col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/CovidCare" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>CovidCare</h3>
                  <span>Home</span>
                </div>
                <img class="img-fluid" src="images/health.jpg" />
              </router-link>
            </div>
            <div class="item photography col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/Recipe" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>Recipe retrieval</h3>
                  <span>App</span>
                </div>
                <img class="img-fluid" src="images/recipes.jpg" />
              </router-link>
            </div>
            <div class="item branding col-sm-6 col-md-4 col-lg-4 mb-4">
              <router-link to="/Job" class="item-wrap fancybox">
                <div class="work-info">
                  <h3>Job website</h3>
                  <span>App</span>
                </div>
                <img class="img-fluid" src="images/job.jpg" />
              </router-link>
            </div>
          </div>
        </div>
      </section>
    </div>

    <!-- End  Works Section -->
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Reggae+One&display=swap");

body {
  font-size: 25px;
  letter-spacing: 2px;
  word-spacing: 2px;
  color: #000000;
  font-weight: normal;
  text-decoration: none;
  font-style: normal;
  font-variant: normal;
  text-transform: none;
}
a {
  color: #222;
  transition: all 0.3s ease;
  text-decoration: none;
}
a:hover {
  text-decoration: none;
}
.weight-500 {
  font-weight: 500;
}
.weight-600 {
  font-weight: 600;
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
.navbar-nav {
  font-weight: 600;
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
.btn-outline-primary {
  color: #625cfe;
  border-color: #625cfe;
}
.btn-outline-primary:hover {
  background-color: #625cfe;
}
.btn-link {
  color: #625cfe;
  transition: all 0.3s ease;
  font-weight: bold;
  font-size: 13px;
  letter-spacing: 1px;
  text-transform: uppercase;
}
.btn-link:hover {
  color: #625cfe;
  opacity: 0.5;
  text-decoration: none;
}
::placeholder {
  font-size: 13px;
  font-weight: 600;
}
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.active,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .show > .nav-link {
  color: #625cfe;
}
.navbar-expand-lg .navbar-nav .nav-link {
  padding-right: 1rem !important;
  padding-left: 1rem;
}
.active a {
  font-weight: bold;
}
.display-5 {
  font-size: 2.5rem;
  font-weight: 300;
  line-height: 1.2;
}
.bg-circle {
  background: url(/images/bg-circle.png) no-repeat left top;
  height: 50px;
  display: flex;
  align-items: center;
  padding-left: 21px;
}
.tt {
  color: #2dcbbd;
}
.circle-new {
  position: absolute;
  top: -10px;
  left: -10px;
  background-color: #2dcbbd;
  width: 60px;
  height: 60px;
  border-radius: 60px;
  display: flex;
}
a.text-blue {
  color: #625cfe;
}
.bubble {
  background: url(/images/bubble.png) no-repeat right bottom;
}
@media (max-width: 700px) {
  p {
    font-size: 13px;
  }
}
#parallax {
  position: relative;
  width: 100%;
  height: 800px;
  background-image: url(/images/back-1.jpg), url(/images/back-2.jpg),
    url(/images/back-3.png);
  background-repeat: no-repeat;
  background-position: center;
  background-position: 50% 50%;
  border-top-right-radius: 15px;
  border-top-left-radius: 15px;
}
.bg-new-3 {
  background: linear-gradient(
      rgba(255, 255, 255, 0.95),
      rgba(255, 255, 255, 0.95)
    ),
    url(/images/back-4.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
}
.tt {
  overflow: hidden;
}
.tt img {
  width: 170px;
  height: 170px;
  border-radius: 170px;
}
.scrollDown {
  position: absolute;
  bottom: 80px;
  left: 50%;
  transform: translate(-50%, -50%) rotate(-180deg);
}
.scrollDown i {
  position: absolute;
  bottom: 10px;
  color: #ccc;
  font-weight: 500;
  font-size: 18px;
  animation: scrollDown 2s ease infinite;
}
@keyframes scrollDown {
  0%,
  100% {
    bottom: 0;
  }
  50% {
    bottom: 10px;
  }
}
.yy {
  margin-bottom: 40px;
}
.yy img {
  filter: grayscale(90%);
  opacity: 0.3;
  cursor: pointer;
  transition: all 0.3s ease;
  height: 30px;
  width: auto;
}
.yy img:hover {
  filter: grayscale(10%);
  opacity: 0.9;
}
.bg-2 {
  background: url(/images/banner-image-seventeen.jpg);
  background-size: cover;
  background-position: center;
}
.bg-new {
  transition: all 0.3s ease;
  cursor: pointer;
  background-color: #a3edd8;
}
.bg-new:hover {
  transform: scale(1.04);
}
.bg-new-2 {
  transition: all 0.3s ease;
  cursor: pointer;
  background-color: #f4df64;
}
.bg-new-2:hover {
  transform: scale(1.04);
}
.nn img {
  transition: all 0.3s ease;
  cursor: pointer;
}
.nn img:hover {
  transform: scale(1.04);
}
.uu li {
  padding-top: 12px;
  font-weight: 600;
  color: #162746;
  font-size: 15px;
}
h4.bg-heading {
  background-color: #8bd3bf;
  padding: 10px 20px;
  font-size: 16px;
  font-weight: 600;
  display: inline-block;
  border-radius: 5px;
}
h4.bg-heading2 {
  background-color: #ffe131;
  padding: 10px 20px;
  font-size: 16px;
  font-weight: 600;
  display: inline-block;
  border-radius: 5px;
}
.icon-circle-80 {
  transition: all 0.3s ease;
  width: 50px;
  margin: 08px;
  height: 50px;
  border-radius: 50px;
  font-size: 15px;
  border: 2px solid #ebebeb;
  cursor: pointer;
  background-color: #f5f5f5;
}
.icon-circle-80:hover {
  box-shadow: 0px 0px 5px 8px rgba(0, 0, 0, 0.08);
}
.icon-circle-80 i {
  font-size: 15px;
}
.icon-circle-80 a {
  color: #666;
}
.icon-circle-80:hover {
  background-color: #e34c43;
  color: #fff;
}
.icon-circle-80:hover a {
  color: #fff;
}

.bb {
  top: -30px;
  left: -10px;
  position: absolute;
  background-color: #fff;
  border-radius: 100%;
  box-shadow: 15px 20px #888888;
  width: 70px;
  height: 70px;
  display: flex;
  align-items: center;
  transition: all 0.3s ease;
  cursor: pointer;
  justify-content: center;
}

.bb:hover {
  transform: scale(1.04);
}
.bb i {
  font-size: 26px;
  margin: 0;
  padding: 0;
  line-height: 0;
}

.ll i {
  font-size: 26px;
}

.filters a {
  color: #000;
  display: inline-block;
  padding-left: 10px;
  padding-right: 10px;
  position: relative;
}

.filters a:hover,
.filters a:focus,
.filters a:active {
  text-decoration: none;
}

.filters a:hover:before {
  content: "";
  position: absolute;
  left: 10px;
  right: 10px;
  bottom: 0;
  height: 1px;
  background-color: #000;
}

.filters a.active {
  color: #000;
}

.filters a.active:before {
  content: "";
  position: absolute;
  left: 10px;
  right: 10px;
  bottom: 0;
  height: 1px;
  background-color: #000;
}

.item {
  border: none;
  margin-bottom: 30px;
}

.item .item-wrap {
  display: block;
  position: relative;
  overflow: hidden;
}

.item .item-wrap:after {
  z-index: 2;
  position: absolute;
  content: "";
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background: rgba(0, 0, 0, 0.4);
  visibility: hidden;
  opacity: 0;
  transition: 0.3s all ease-in-out;
}

.item .item-wrap img {
  transition: 0.3s transform ease;
  transform: scale(1);
}

.item .item-wrap > .work-info {
  position: absolute;
  top: 50%;
  width: 100%;
  text-align: center;
  z-index: 3;
  transform: translateY(-50%);
  color: #fff;
  opacity: 0;
  visibility: hidden;
  margin-top: 20px;
  transition: 0.3s all ease;
}

.item .item-wrap > .work-info h3 {
  font-size: 20px;
  margin-bottom: 0;
  color: white;
}

.item .item-wrap > .work-info span {
  font-size: 14px;
  text-transform: uppercase;
  letter-spacing: 0.2rem;
}

.item .item-wrap:hover {
  text-decoration: none;
}

.item .item-wrap:hover img {
  transform: scale(1.05);
}

.item .item-wrap:hover:after {
  opacity: 1;
  visibility: visible;
}

.item .item-wrap:hover .work-info {
  margin-top: 0px;
  opacity: 1;
  visibility: visible;
}
</style>