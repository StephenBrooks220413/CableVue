<template>
  <!-- Carousel wrapper -->
  <div
    id="carouselBasicExample"
    class="carousel slide carousel-fade"
    data-ride="carousel"
  >
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li
        data-target="#carouselBasicExample"
        data-slide-to="0"
        class="active"
      ></li>
      <li data-target="#carouselBasicExample" data-slide-to="1"></li>
      <li data-target="#carouselBasicExample" data-slide-to="2"></li>
    </ol>

    <!-- Inner -->
    <div class="carousel-inner">
      <!-- Single item -->
      <div class="carousel-item active">
        <img
          src="http://springcom.com/wp-content/uploads/2014/05/TV-Service1.jpg"
          class="d-block w-100 h-75"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3>Reliable Service</h3>
          <p>Serving community for 17yrs and still growing.</p>
        </div>
      </div>

      <!-- Single item -->
      <div class="carousel-item">
        <img
          src="http://springcom.com/wp-content/uploads/2014/05/TV-Service1.jpg"
          height="240px"
          class="d-block w-100 h-75"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3>Faster Internet</h3>
          <p>Tired of slow DSL? Cable Company overcharge for slow speeds?.</p>
        </div>
      </div>

      <!-- Single item -->
      <div class="carousel-item">
        <img
          src="http://springcom.com/wp-content/uploads/2014/05/TV-Service1.jpg"
          class="d-block w-100 h-75"
          alt="..."
        />
        <div class="carousel-caption d-none d-md-block">
          <h3>Customer Service</h3>
          <p>Quality care fo the best customers in the world.</p>
        </div>
      </div>
    </div>
    <!-- Inner -->

    <!-- Controls -->
    <a
      class="carousel-control-prev"
      href="#carouselBasicExample"
      role="button"
      data-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Previous</span>
    </a>
    <a
      class="carousel-control-next"
      href="#carouselBasicExample"
      role="button"
      data-slide="next"
    >
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="visually-hidden">Next</span>
    </a>
  </div>
  <!-- Carousel wrapper -->
  <br /><br /><br /><br /><br /><br />
  <div class="container">
    <div class="row">
      <div class="col-md-6">
        <img
          src="https://d1sfco99flnudn.cloudfront.net/www.cabletv.com/images/pages/time-warner/hero-index.png"
          alt="side image"
          width="80%"
        />
      </div>
      <div class="col-md-6">
        <div class="row">
          <br /><br />
          <div class="col-md-6">
            <h4>Be Free</h4>
            <ul>
              <li>No Contracts</li>
              <li>No hidden terms</li>
              <li>No cables</li>
            </ul>
          </div>
          <br /><br />
          <div class="col-md-6">
            <h4>Save Today</h4>
            <ul>
              <li>Lowest Cost</li>
              <li>Bundle Here</li>
              <li>More Channels</li>
            </ul>
          </div>
        </div>
      </div>
    </div>
  </div>
  <br /><br />
  <div class="phone">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <h4 style="padding-top: 30%">
            Easy navigation, easy ordering, easy billing, easy service, just
            much easier.
          </h4>
        </div>
        <div class="col-md-6">
          <br /><br /><br />
          <img
            src="https://ntp.niehs.nih.gov/ntp/research/areas/cellphone/cellphone_main.jpg"
            width="70%"
            alt=""
          />
        </div>
      </div>
    </div>
  </div>
  <h2 class="display-4">What's Inside</h2>
  <br /><br />
  <div class="Bg jumbotron"></div>
  <br /><br /><br /><br /><br /><br /><br /><br />
  <div class="container-fluid">
    <!-- code here -->
    <h1 class="display-4 text-center">Service Features</h1>
    <br /><br /><br />
    <div class="row">
      <div class="col-sm-4" style="margin-top:20px">
        <div class="card card-bg1">
          <div class="card-body">
            <h5 class="card-title">Bronze Package</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional
              content.
            </p>
            <a href="mailto:@someon@mail.com" class="btn btn-primary"
              >Inquire</a
            >
          </div>
        </div>
      </div>
      <div class="col-sm-4" style="margin-top:20px">
        <div class="card card-bg2">
          <div class="card-body">
            <h5 class="card-title">Gold Package</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional
              content.
            </p>
            <a href="mailto:@someon@mail.com" class="btn btn-primary"
              >Inquire</a
            >
          </div>
        </div>
      </div>
      <div class="col-sm-4" style="margin-top:20px">
        <div class="card card-bg3">
          <div class="card-body">
            <h5 class="card-title">Platinum Package</h5>
            <p class="card-text">
              With supporting text below as a natural lead-in to additional
              content.
            </p>
            <a href="mailto:@someon@mail.com" class="btn btn-primary"
              >Inquire</a
            >
          </div>
        </div>
      </div>
    </div>
  </div>
  <br /><br /><br /><br /><br /><br />
  <!-- Carousel wrapper -->
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.Bg {
  background: url(https://hibusiness.ca/wp-content/uploads/2016/10/ON-CableBox-and-Remote-1024x486.jpg)
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: 50vh;
}
.bg-text {
  color: white;
  padding-top: 45px;
  display: block;
  width: 110px;
  margin-left: 20%;
  font-size: 2em;
}
.img-shadow {
  border-bottom: 1px groove lightgrey;
  width: 70%;
  box-shadow: 8px 6px 7px 10px rgb(168, 166, 166);
}
.phone {
  background: url(https://i.stack.imgur.com/lnuwK.png) no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: 60vh;
  margin-bottom: 190px;
  margin-top: 90px;
}
@media (max-width: 768px) {
  .phone {
    background: none;
    width: 100%;
    height: 70vh;
    margin-bottom: 285px;
    margin-top: 10px;
  }
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
.card-bg1 {
  background: url(http://www.trbimg.com/img-5aba84c4/turbine/ct-ent-rescan-tv-channel-antenna-0328)
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
}
.card-bg2 {
  background: url(https://i.ytimg.com/vi/dmghBUlfZdY/maxresdefault.jpg)
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
}
.card-bg3 {
  background: url(http://www.abouttechnology.us/wp-content/uploads/2019/04/7.jpg)
    no-repeat center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  width: 100%;
  height: auto;
  color: white;
}
.customer-img {
  max-width: 450px;
  max-height: 300px;
  margin-left: auto;
  margin-right: auto;
}
</style>
