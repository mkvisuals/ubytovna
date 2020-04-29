<template>
  <main>
    <ApartmentBlock />
  </main>
</template>

<!--pokud se tahle komponenta načte, tak se styly aplikují všude-->
<style>
</style>

<!--tyhle styly scoped jsou jenom pro tuhle komponentu a jinam se nepropisou, cool huh?-->
<style scoped>
</style>
<script>
  import ApartmentBlock from "./ApartmentBlock";

  export default {
    components: {ApartmentBlock}
  }
</script>
