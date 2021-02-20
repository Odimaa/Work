<template>
  <section class="section pt-5">
    <div class="container">
      <div class="row mb-4 align-items-center">
        <div class="col-md-6" data-aos="fade-up">
          <h2>Job Listing app</h2>
        </div>
      </div>
    </div>

    <div class="site-section pb-0">
      <div class="container">
        <div class="row align-items-stretch">
          <div class="col-md-8" data-aos="fade-up">
            <img src="images/job.jpg" alt="Image" class="img-fluid" />
          </div>
          <div class="col-md-3 ml-auto" data-aos="fade-up" data-aos-delay="100">
            <div class="sticky-content">
              <h4 style="text-decoration: underline" class="h4 mb-3">
                What I used
              </h4>
              <ul class="list-unstyled list-line mb-5">
                <li>Design</li>
                <li>HTML/CSS</li>
                <li>Tailwind</li>
                <li>React</li>
              </ul>

              <p>
                <a href="https://odi-react-job.netlify.app/" class="readmore"
                  >Visit Website</a
                >
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Montserrat&family=Reggae+One&display=swap");

.readmore {
  display: inline-block;
  border: 1px solid #000;
  padding: 10px 15px;
  font-size: 12px;
  text-transform: uppercase;
  color: #000;
  transition: 0.2s all ease;
  font-weight: 700;
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

section {
  margin-top: 150px;
  padding-bottom: 150px;
}

ul {
  font-family: "Reggae One", cursive;
  font-size: 14px;
  line-height: 24px;
}
.readmore:active,
.readmore:focus,
.readmore:hover {
  outline: none;
}

.readmore:hover {
  color: #fff;
  text-decoration: none;
  background: #000;
}
</style>