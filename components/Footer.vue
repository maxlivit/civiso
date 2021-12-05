<template>
  <footer class="footer-container">
    <div class="container c-form ">
    <div class="form">

      <div class="form-container row">
        <div class="newsletter"></div>

        <div class="newsletter">
        <h1 class="newsletter-text">
          <span class="orange">&#160;</span>
          Join our newsletter &#160;
        </h1>

          <input class="email-input" placeholder="Email"/>
        </div>
      </div>
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
  display: flex;
  justify-content: center;
  background: url('/images/footer-img.jpg') no-repeat center center;
  height: 30vw;
  background-size: 100% auto;
}

.row {
  display: flex;
  justify-content: center;
  align-content: center;
}

.form {
  h1 {
    background-color: rgba(243, 243, 243, 0.3);
    font-size: 3rem;
    display: inline-block;
    color: white;
    margin-bottom: 0.75rem;
  }

  input {
    border-radius: 2rem;
    border: none;
    padding: 0.5rem 1rem;
    font-size: 1.1rem;
    font-family: 'Work Sans', sans-serif;
    display: inline-block;
    width: 60%;
  }
}

.orange {
 background-color: #F5A201;
}
.newsletter {
  display: flex;
  flex-direction: column;
  flex: 50%;
  height: 100%;
  align-items: center;
}

.c-form {
  width: 100%;
}


</style>
