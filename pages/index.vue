<template>
  <div>
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>
<script>
  import Header from "~/components/layout/Header";
  import Main from "~/components/layout/Main";
  import Footer from "~/components/layout/Footer";

  export default {
    components: {Header, Main, Footer}
  }
</script>
