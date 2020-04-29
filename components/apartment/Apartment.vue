<template>
  <div>
    <h3>{{ name }}</h3>
    <span>{{ description }}</span>
    <img v-if="image" :src="image" alt="codko vole">
    <div else>
      zmrdi mi nedali obrazek
    </div>
  </div>
</template>

<script>

export default {
  name: 'Apartment',
  props: ['name', 'description', 'image'],
  data () {
    return {
    }
  }
}
</script>

<style scoped>

</style>
