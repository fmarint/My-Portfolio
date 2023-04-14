<template>

  <!-- <nav>
    <RouterLink to="/">Home</RouterLink>
    <RouterLink to="/about">About</RouterLink>
  </nav> -->
  
  <li>
    <a :class="isActive ? 'active' : ''" :href="href" >
      {{ text }}<span></span>
     </a>
  </li>
</template>

<script>
export default {
  data() {
    return {};
  },
  props: {
    isActive: true,
    href: "#top",
    text: "Home",
  },
};
</script>

<style>
</style>