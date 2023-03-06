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
    <div class="row carousel">
      <div class="slider">
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 img-fluid rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 img-fluid rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 img-fluid rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 img-fluid rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-2 me-3">
          <div class="card">
            <div class="card-body">
              <div class="image-container">
                <img
                  class="news-img-1 img-fluid rounded"
                  src="../assets/Rectangle1.png"
                  alt="Image description"
                />
                <div class="text-overlay">
                  <p class="title-3">Заголовок текста</p>
                </div>
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
      slidesToShow: 6,
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
