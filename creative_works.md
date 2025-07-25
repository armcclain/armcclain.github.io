---
title: "design"
permalink: "/design/"
layout: page
---

in my free time you will find me fiddling with hex codes and designing graphics for dc community groups and university programming. want to talk art and science? drop me a line. 

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
