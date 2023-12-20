<template>
  <NavBar/>
  <main class="container-fluid">
    <router-view/>
  </main>
  <FooterComp/>
</template>

<script>
import FooterComp from './components/FooterComp.vue';
import NavBar from './components/NavBar.vue';

export default {
  components: {
    NavBar,
    FooterComp
}
}
</script>

<style src="@/assets/CSS/styles.css"></style>
