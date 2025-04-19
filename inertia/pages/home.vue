<script setup lang="ts">
  import { Head } from '@inertiajs/vue3'
</script>

<template>
  <Head title="Homepage" />
  
  <!-- Background striping -->
  <div class="fixed xl:absolute left-8 right-8 top-0 bottom-0 xl:inset-0 max-w-screen-xl mx-auto before:content-[''] before:[background:repeating-linear-gradient(0deg,var(--sand-5)_0_4px,transparent_0_8px)] before:absolute before:top-0 before:left-0 before:h-full before:w-px after:content-[''] after:[background:repeating-linear-gradient(0deg,var(--sand-5)_0_4px,transparent_0_8px)] after:absolute after:top-0 after:right-0 after:h-full after:w-px"></div>

  <!-- Center the container using flexbox -->
  <div class="pt-4 h-screen flex flex-col items-center justify-center">
    <div class="container text-center">
      <div class="info">
        <strong>Nama:</strong> M Asngad
      </div>
      <div class="info">
        <strong>NIM:</strong> 23EO10053
      </div>
      <div class="info">
        <strong>Prodi:</strong> Informatika
      </div>
    </div>
  </div>
</template>

<style scoped>
html, body {
  height: 100%;
  margin: 0;
}

.container {
  padding: 20px;
  background-color: white;
  border-radius: 10px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.info {
  margin: 10px 0;
  font-size: 18px;
}

strong {
  color: #007BFF;
}
</style>
