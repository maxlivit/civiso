<template>
  <div>
    <Navbar />

    <div class="container">
      <Nuxt />
    </div>

    <Footer />
  </div>
</template>
<script>
import Navbar from "../components/Navbar";
export default {
  components: {Navbar}
}
</script>
