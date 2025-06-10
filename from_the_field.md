---
title: "from the field"
permalink: "/from-the-field/"
layout: page
---

to learn more about life at Gombe head over to <a href="https://www.instagram.com/the_primate_diaries/?igsh=dHhtM2F2ZXMxdWNv&utm_source=qr#" style="color: #840032;"><strong>instagram</strong></a>! In the meanwhile, here are some highlights.

<!-- Swiper.js CDN -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />
<script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>

<style>

 .swiper-container {
  width: 100%;
  max-width: 800px;
  margin: auto;
  padding-bottom: 40px; /* Extra space for pagination */
  position: relative; /* Required for positioning arrows correctly */
}

.swiper-wrapper {
  display: flex;
}

.swiper-slide {
  display: flex;
  justify-content: center;
  align-items: center;
}

.swiper-slide img {
  max-width: 100%;
  max-height: 80vh;
  width: auto;
  height: auto;
  object-fit: contain;
  border-radius: 8px;
}

/* Move pagination BELOW the carousel */
  .swiper-pagination {
    position: relative;
    bottom: -50px; /* Moves it further below */
    z-index: 10;
  }

/* Default dot color */
.swiper-pagination-bullet {
  background: gray;
  opacity: 0.5;
}

/* Active (highlighted) dot color */
.swiper-pagination-bullet-active {
  background: #850032;
  opacity: 1;
}

/* Style for the arrows */
.swiper-button-prev,
.swiper-button-next {
  color: #850032; /* Change the arrow color */
  position: absolute;
  bottom: 10px; /* Position arrows at the bottom */
  z-index: 10;
  font-size: 24px; /* Adjust arrow size */
}

/* You can customize the appearance more by adding background or borders */
.swiper-button-prev {
  left: 10px; /* Position the previous arrow to the left */
}

.swiper-button-next {
  right: 10px; /* Position the next arrow to the right */
}
</style>

<h2>select projects</h2>


<!-- Swiper Carousel -->
<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/e05021ad-40c8-44e7-a23c-bcf00a882d07" alt="Abby Follow" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/479f06d8-adf4-49dd-85d3-3f3fbccc11ee" alt="Termite" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/4cf453dd-9a7b-4677-8325-652d3671a5e5" alt="Fadhila et al" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/14e610ce-1d07-4819-bc83-5cfdb14a0307" alt=" Tanga Honey" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/0151df5f-fdb5-4df6-95cc-43548d8e5bfa" alt="Sims and Abby" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/cf8d68eb-8d48-4f40-a1b4-7afba4408070" alt="Abby and Fudge" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/e9f96b88-d11a-45ad-a9be-cf0614f787a8" alt="Sunset" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/b2258b73-2664-4728-80c4-40d68573fe9e" alt="Schwali" />
    </div>
  </div>



  <!-- Navigation Buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>
</div>

<!-- Pagination Outside the Carousel -->
<div class="swiper-pagination"></div>

<script>
  var swiper = new Swiper(".swiper-container", {
    loop: true,
    spaceBetween: 3, // Reduce space between slides
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    autoplay: {
      delay: 7000, // Increase slide duration to 5 seconds
    },
  });
</script>
