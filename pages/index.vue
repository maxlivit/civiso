<template>
  <div>
    <div class="section">
      <div class="section-heading">
        <h1>Our Departments.</h1>
        <p>How Civiso is getting its message across</p>
      </div>
        <div class="department">
          <div class="image-containers">
            <div class="image-comp">
              <img src="images/department/first.png" />
            </div>
            <div class="image-comp">
              <img src="images/department/second.png" />
            </div>
          </div>

            <div>
              <div class="image-comp">
              <img src="images/department/third.png" />
              </div>
              <div class="image-comp">
              <img src="images/department/third.png" />
                </div>
            </div>
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

      <div class="calls">
       <div class="calls-images">
         <img src="/images/calls/calls-1.png" />
         <img src="/images/calls/calls-2.png" />
         <img src="/images/calls/calls-3.png" />
       </div>
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

.department {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-content: center;
  margin-bottom: 2rem;

  img {
    width: 300px;
  }
}


.calls {
  padding-top: 2rem;

  .calls-images {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-content: flex-start;
  }
}

</style>
