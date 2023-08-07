<template>
<div id="carouselExampleCaptions" class="carousel slide">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
    <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active position-relative">
      <div class="position-absolute top-0 start-0 m-3">
        <button class="btn btn-info p-4 pb-3">
          <h1 class="fw-bold">GARMENTPLANX</h1>
        </button>
      </div>
      <img src="../../public/BannerA.jpg" class="d-block w-100" alt="Banner A">
      <div class="carousel-caption d-none d-md-block">
        <RouterLink :to="{ name: 'home' }" class="btn btn-primary fw-bold mb-5 rounded-pill ps-5 pe-5 pt-3 pb-3">WHAT IS GARMENTPLANX ?</RouterLink>
      </div>
    </div>
    <div class="carousel-item position-relative">
      <div class="position-absolute top-0 start-0 m-3">
        <button class="btn btn-info p-4 pb-3">
          <h1 class="fw-bold">GARMENTPLANX</h1>
        </button>
      </div>
      <img src="../../public/BannerB.jpg" class="d-block w-100" alt="Banner B">
      <div class="carousel-caption d-none d-md-block">
        <RouterLink :to="{ name: 'home' }" class="btn btn-primary fw-bold mb-5 rounded-pill ps-5 pe-5 pt-3 pb-3">HOW DO I USE IT ?</RouterLink>
      </div>
    </div>
    <div class="carousel-item position-relative">
      <div class="position-absolute top-0 start-0 m-3">
        <button class="btn btn-info p-4 pb-3">
          <h1 class="fw-bold">GARMENTPLANX</h1>
        </button>
      </div>
      <img src="../../public/BannerC.jpg" class="d-block w-100" alt="Banner C">
      <div class="carousel-caption d-none d-md-block">
        <RouterLink :to="{ name: 'home' }" class="btn btn-primary fw-bold mb-5 rounded-pill ps-5 pe-5 pt-3 pb-3">WHAT ABOUT MY PRIVACY AND DATA ?</RouterLink>
      </div>
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>
</template>

<style scoped>
  .btn-info {
    font-family: 'Bebas Neue', sans-serif;
    background-color: #FFFFFF;
    border: #FFFFFF;
    color: #00CED1;
    border-radius: 30px;
    pointer-events: none;
  }
  img.d-block {
    height: 100vh;
    object-fit: cover;
  }
  .carousel-indicators button {
    width: 10px;
    height: 10px;
    border-radius: 100%;
  }
  .carousel-indicators .active {
    background-color: #FF5C00 !important;
  }
</style>