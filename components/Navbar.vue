<template>
  <nav>
    <div class="navbar container">
      <NuxtLink to="/">
        <img src="images/logo.png" alt="civiso logo" />
      </NuxtLink>
      <ul class="menu">
        <li><NuxtLink to="/mission">mission.</NuxtLink></li>
        <li><NuxtLink to="/mission">team.</NuxtLink></li>
        <li><NuxtLink to="/mission">contact.</NuxtLink></li>
        <li><NuxtLink to="/mission" id="highlight">join.</NuxtLink></li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss">
@import "../assets/global.scss";

nav {
  position: fixed;
  top: 0;
  width: 100%;
  background: rgba($background-color, 0.95);
  z-index: 1;
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
  a {
    color: black;
    text-decoration: none;
  }
}
</style>
