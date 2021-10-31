<template>
  <div>
    <div class="section">
      <div class="section-heading">
        <h1>Our Departments.</h1>
        <p>How Civiso is getting its message across</p>
      </div>
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Our Partners & Affiliates.</h1>
        <p>The team at Civiso has the active support of faculty from</p>
      </div>
      <AffiliatesSlider />
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Civiso: <span class="highlight">Inspired.</span></h1>
        <p>Calls to action written by our very own members</p>
      </div>
    </div>

    <div class="section">
      <div class="section-heading">
        <h1>Civiso:  <span class="highlight">Toks.</span></h1>
        <p>Raising awareness in 60 seconds or less.</p>
      </div>
    </div>
  </div>
</template>

<script>
import AffiliatesSlider from "../components/AffiliatesSlider";
export default {
  components: {AffiliatesSlider}
}
</script>

<style lang="scss">
 .section {
   margin: 6rem 0;
 }

.section-heading {
  h1 {
    margin-bottom: 0.75rem;
  }

  margin-bottom: 2rem;
}

</style>
