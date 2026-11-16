<template>
  <div class="google-map">
    <iframe id="gmap_canvas" :src="mapSrc"></iframe>
  </div>
</template>

<script setup>
const mapSrc =
  'https://maps.google.com/maps?q=Plot+no+33+Lane+no+5+Vishanpuri+colony+mundera+Prayagraj+211011&t=&z=14&ie=UTF8&iwloc=&output=embed';
</script>
