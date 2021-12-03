<template>
  <footer class="footer-container">
    <div class="container form">

      <div class="form-container">
        <div class="newsletter">
        <h1 class="newsletter-text">
          <span class="orange">&#160;</span>
          Join our newsletter
        </h1>
        </div>
        <input class="email-input"/>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
}
</script>
<style lang="scss">
.footer-container {
  background: url('/images/footer-img.jpg') no-repeat center center;
  height: 30vw;
  background-size: 100% auto;
}

.form-container {
  display: flex;
  flex-direction: column;
  justify-content: flex-end;
  width: 40%;

  h1 {
    font-size: 2.5rem;
  }

  input {
    border-radius: 2rem;
    border: none;
  }
}


.newsletter-text {
  color: white;
  background-color: rgba(243, 243, 243, 0.2);
}

.orange {
 background-color: #F5A201;
}

</style>
