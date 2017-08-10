<template>
  <v-carousel icon="stop">
    <v-carousel-item v-for="(item,i) in items" v-bind:src="item.src" :key="i"></v-carousel-item>
  </v-carousel>
</template>

<script>
export default {
  data () {
    return {
      items: [
        {
          src: 'http://clipart-library.com/img/934470.png'
        },
        {
          src: 'http://www.miracolo.sk/images/travaakvietky.png'
        }
      ]
    }
  }
}
</script>

<style>
  
</style>
