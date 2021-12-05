<template>
<nav>
  <div class="navbar container">
  <img src="images/logo.png" alt="civiso logo"/>
  <ul class="menu">
    <li>mission.</li>
    <li>team.</li>
    <li>contact.</li>
    <li class="highlight">join.</li>
  </ul>
  </div>
</nav>
</template>

<script>
export default {
 name: 'Navbar'
}
</script>

<style lang="scss">
@import '../assets/global.scss';

nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba($background-color, 0.95);
}

.navbar {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  margin: 1rem auto;

  img {
    height: fit-content;
  }

  ul {
    display: flex;
    flex-direction: row;
    list-style: none;
    margin-top: 1rem;
  }

  li {
    font-weight: 700;
    font-size: 1.1rem;
    margin: 0 1rem;
  }
}

</style>
