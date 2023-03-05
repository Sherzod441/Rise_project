<template>
  <div>
    <section id="hero-section">
      <div class="hero-img">
        <div class="container">
          <div class="row">
            <div class="col-md-4">
              <div class="about-us">
                <h1 class="text-white">Biz Haqimizda</h1>
              </div>
            </div>
            <div class="col-md-4"></div>
            <div class="col-md-4">
              <div class="about-text">
                <p class="text-white">
                  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
                  Blanditiis, animi?
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="hero-card">
        <div class="container">
          <div class="row">
            <div class="col-md-4">
              <div class="card card-body p-4 border-0">
                <div class="card-title">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquam, recusandae!
                </div>
                <div class="card-subtitle">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi
                  nemo esse sapiente quas. Consectetur amet aut beatae deleniti
                  architecto neque?
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="card card-body p-4 border-0">
                <div class="card-title">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquam, recusandae!
                </div>
                <div class="card-subtitle">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi
                  nemo esse sapiente quas. Consectetur amet aut beatae deleniti
                  architecto neque?
                </div>
              </div>
            </div>
            <div class="col-md-4">
              <div class="card card-body p-4 border-0">
                <div class="card-title">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit.
                  Aliquam, recusandae!
                </div>
                <div class="card-subtitle">
                  Lorem ipsum dolor sit amet consectetur adipisicing elit. Sequi
                  nemo esse sapiente quas. Consectetur amet aut beatae deleniti
                  architecto neque?
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="video-banner">
      <div class="container">
        <div class="video">
          <div class="video-text d-flex justify-content-between text-white p-4">
            <div class="h1-text text-uppercase">
              Videoda Rise haqida batafsil ma’lumot berilgan
            </div>
            <div class="p-text">Video davomiyligi: 4 daqiqa</div>
          </div>
          <div class="video-icon">
            <img src="../assets/play.png" alt="play video" />
          </div>
        </div>
        <p class="mt-2">“RISE” kompaniyasi haqida video:</p>
      </div>
    </section>
    <section id="teams">
      <div class="container">
        <div class="team-text col-md-12">
          <small class="">Jamoamiz</small>
          <small class="display-6"
            >Jamoamiz haqida yaqindan tanishishingiz uchun biz
            tanishtiramiz.</small
          >
        </div>
        <SliderVue />
        <div class="team">
          <div class="row">
            <div class="col-md-4">
              <div class="card border-0 img-center"></div>
            </div>
            <div class="col-md-4">
              <div class="card border-0 img-top"></div>
            </div>
            <div class="col-md-4">
              <div class="card card-body border-0 card-center-text">
                <div class="card-title">
                  <h3>O‘rnatish uchun qulay bo‘lgan mahsulotlar</h3>
                </div>
                <div class="card-subtitle">
                  <p>
                    Bizning jahonga mashhur brend kompaniyalari tomonidan ishlab
                    chiqarilgan gipsokarton mahsulotlari bilan bemalol
                    raqobatlasha oladigan sifatli gipsokartonlarimiz o‘rnatish
                    uchun juda ham qulay hisoblanadi.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import SliderVue from "@/components/Slider.vue";
// import "slick-carousel/slick/slick.css";
// import "slick-carousel/slick/slick-theme.css";
// import $ from "jquery";
// import "slick-carousel";

export default {
  name: "AboutView",
  components: {
    SliderVue,
  },
  data() {
    return {};
  },
};
</script>

<style scoped>
@import url("../assets/css/about.css");
</style>
