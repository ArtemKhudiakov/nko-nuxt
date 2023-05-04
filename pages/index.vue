<template>
  <div>
    <nav class="navigation">
      <nuxt-link exact class="navigation__link" to="/">Main</nuxt-link>
      <nuxt-link class="navigation__link" to="/about">About us</nuxt-link>
      <nuxt-link class="navigation__link" to="/id">Id</nuxt-link>
    </nav>

    <Tutorial/>
  </div>
</template>

<script>
export default {
  // name: 'IndexPage'
}
</script>


<style>

.navigation {
  display: flex;
  justify-content: space-evenly;
  align-content: center;
  height: 50px;
  margin: 0 auto;
  font-size: 20px;

}

</style>
