<script setup>
import { RouterLink, RouterView } from 'vue-router'
import SidebarComponent  from "./components/SidebarComponent.vue";
</script>

<template>
  <header>
    <div class="container-fluid g-0">
      <div class="row g-0">
        <div class="col-lg-6 col-md-6 col-sm-12">
          <!-- image Component -->
          <SidebarComponent/>
        </div>
        <div class="col-lg-6 col-md-6 col-sm-12">
          <!-- form -->
          <RouterView/>
        </div>
      </div>
    </div>
  </header>
</template>

<style scoped>
img.img-fluid {
  width: 100%;
  height: 100vh !important;
  object-fit: cover;
}

</style>
