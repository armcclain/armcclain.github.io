---
title: "creative works"
permalink: "/creative-works/"
layout: page
---

in my free time you will find me fiddling with hex codes and designing graphics for dc community groups and university programming. this space is a work in progress still — stay tuned for exciting updates soon.

<!-- Swiper.js CDN -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />
<script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>

<style>
  .swiper-container {
    width: 100%;
    max-width: 800px;
    margin: auto;
  }
  
  .swiper-wrapper {
    display: flex; /* Ensures all slides are in one row */
  }

  .swiper-pagination {
  position: absolute;
  bottom: 1px; /* Moves the dots closer to the bottom */
  transform: translateX(-50%);
  z-index: 10;
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
    border-radius: 3px;
  }
</style>

<h2>select projects</h2>

<!-- Swiper Carousel -->
<div class="swiper-container">
  <div class="swiper-wrapper">
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/ba370982-70ff-447f-be86-80ee9bc45a23" alt="Hart Foam Poster Print" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/f53f856d-65e8-4a31-887d-3fed6d8be2ac" alt="Large Square Sign" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/e42e7276-77db-4e96-ae89-20fc1ac4855a" alt="Can I Sleep in Your Brain" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/ff6f7746-7416-4731-8849-f7f94fd656fd" alt="CASHP 25" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/5f6a6da3-7e6a-43eb-9227-31571331c840" alt="Primatology" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/e127deab-311e-43a2-a6df-678c4cf75083" alt="Archaeology" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/c010d3dd-6322-488a-999b-34f60f173270" alt="Mind/Brain" />
    </div>
    <div class="swiper-slide">
      <img src="https://github.com/user-attachments/assets/98e95945-1ceb-492c-a135-e4e293100325" alt="Paleoarchaeology" />
    </div>
  </div>

  <!-- Navigation Buttons -->
  <div class="swiper-button-prev"></div>
  <div class="swiper-button-next"></div>

  <!-- Pagination Dots -->
  <div class="swiper-pagination"></div>
</div>

<script>
  var swiper = new Swiper(".swiper-container", {
    loop: true,
    spaceBetween: 3, // Reduced space between slides
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    autoplay: {
      delay: 5000, // Increased slide duration to 5 seconds
    },
  });
</script>

