<template>
  <div>
    <h2>Byty pičo</h2>
    <template v-for="apartment in apartments">
      <Apartment :name="apartment.name" :description="apartment.description" :image="apartment.image" />
    </template>
  </div>
</template>

<script>
  import image from '../../assets/images/cod2.jpg';
  import Apartment from "../apartment/Apartment";

  export default {
    name: "ApartmentBlock",
    components: {Apartment},
    data() {
      return {
        apartments: [
          {
            name: 'test1',
            description: 'popis vole',
            image: image
          }
        ],
      }
    },
  }
</script>

<style scoped>

</style>
