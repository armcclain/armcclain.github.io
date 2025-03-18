---
title: "creative Works"
permalink: "/creative-works/"
layout: page
---

<head>
  <!-- Swiper.js CDN -->
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.css" />
  <script src="https://cdn.jsdelivr.net/npm/swiper/swiper-bundle.min.js"></script>
  
  <style>
    .swiper-container {
      width: 100%;
      max-width: 800px;
      margin: auto;
    }
    
    .swiper-slide {
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .swiper-slide img {
      max-width: 100%;
      max-height: 80vh; /* Adjust max height dynamically */
      width: auto;
      height: auto;
      object-fit: contain;
      border-radius: 8px;
    }
  </style>
</head>

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
    navigation: {
      nextEl: ".swiper-button-next",
      prevEl: ".swiper-button-prev",
    },
    pagination: {
      el: ".swiper-pagination",
      clickable: true,
    },
    autoplay: {
      delay: 3000,
    },
  });
</script>
