<template>
  <div> 
    <h1>random title</h1>
    <photo-gallery></photo-gallery>
    <stepper></stepper>
  </div>
</template>
<script>
import PhotoGallery from '~/components/Carrousel.vue'
import Stepper from '~/components/Stepper.vue'
export default {
  components: {
    PhotoGallery,
    Stepper
  }
}
</script>

<style>
</style>
