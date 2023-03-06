<template>
  <div class="team-carousel mt-3">
    <div class="row">
      <div class="col-12">
        <div class="carousel-icon float-end">
          <div class="icon-img my-2">
            <img src="../assets/prev.png" class="me-3 prev" alt="Prev Icon" />
            <img src="../assets/next.png" class="next" alt="Next Icon" />
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="slider">
        <div class="col-md-4">
          <div class="card card-body border-0 d-flex p-4 me-2">
            <div class="d-flex justify-content-between">
              <div class="team-img">
                <div class="row">
                  <div class="col-md-3">
                    <img src="../assets/team2.png" alt="" />
                  </div>
                  <div class="col-md-9">
                    <p class="mb-0 text-capitalize text-white">bahodir jalilov</p>
                    <small>Menejer</small>
                  </div>
                </div>
              </div>
              <div class="team-url pe-2 pt-2">
                <img src="../assets/vec.png" alt="Vector img" />
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card card-body border-0 d-flex p-4 me-2">
            <div class="d-flex justify-content-between">
              <div class="team-img">
                <div class="row">
                  <div class="col-md-3">
                    <img src="../assets/team2.png" alt="" />
                  </div>
                  <div class="col-md-9">
                    <p class="mb-0 text-capitalize text-white">bahodir jalilov</p>
                    <small>Menejer</small>
                  </div>
                </div>
              </div>
              <div class="team-url pe-2 pt-2">
                <img src="../assets/vec.png" alt="Vector img" />
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card card-body border-0 d-flex p-4 me-2">
            <div class="d-flex justify-content-between">
              <div class="team-img">
                <div class="row">
                  <div class="col-md-3">
                    <img src="../assets/team2.png" alt="" />
                  </div>
                  <div class="col-md-9">
                    <p class="mb-0 text-capitalize text-white">bahodir jalilov</p>
                    <small>Menejer</small>
                  </div>
                </div>
              </div>
              <div class="team-url pe-2 pt-2">
                <img src="../assets/vec.png" alt="Vector img" />
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card card-body border-0 d-flex p-4 me-2">
            <div class="d-flex justify-content-between">
              <div class="team-img">
                <div class="row">
                  <div class="col-md-3">
                    <img src="../assets/team2.png" alt="" />
                  </div>
                  <div class="col-md-9">
                    <p class="mb-0 text-capitalize text-white">bahodir jalilov</p>
                    <small>Menejer</small>
                  </div>
                </div>
              </div>
              <div class="team-url pe-2 pt-2">
                <img src="../assets/vec.png" alt="Vector img" />
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import "slick-carousel";
import "slick-carousel/slick/slick.css";
import "slick-carousel/slick/slick-theme.css";
import $ from "jquery";
export default {
  name: "Slider",
  mounted() {
    $(".slider").slick({
      slidesToShow: 3,
      arrows: true,
      autoplay: true,
      responsive: [
        {
          breakpoint: 768,
          settings: {
            slidesToShow: 2,
          },
        },
        {
          breakpoint: 576,
          settings: {
            slidesToShow: 1,
          },
        },
      ],
    });
    const $prev = $(".icon-img .prev");
    const $next = $(".icon-img .next");
    $prev.on("click", () => {
      $(".slider").slick("slickPrev");
    });

    $next.on("click", () => {
      $(".slider").slick("slickNext");
    });
  },
};
</script>

<style scoped></style>
