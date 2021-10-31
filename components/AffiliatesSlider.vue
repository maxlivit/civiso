<template>
  <div class="affiliates">
    <img src="images/cuny.png" alt="CUNY"/>
    <img src="images/harvard.png" alt="Harvard"/>
    <img src="images/fit.png" alt="FIT" />
    <img src="images/photography.png" alt="Photography" />
    <img src="images/pfp.png" alt="PFP" />
  </div>
</template>

<script>
export default {
  name: 'AffiliatesSlider'
}
</script>
<style lang="scss">

.affiliates {
  display: flex;
  flex-direction: row;
  overflow: auto;

  &::-webkit-scrollbar {
   display: none;
  }

  -ms-overflow-style: none;
  scrollbar-width: none;
}

.affiliates > img {
  margin: 2rem;
  max-height: 200px;
}


</style>
