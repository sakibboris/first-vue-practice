<template>
  <!-- <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container px-lg-5">
      <a class="navbar-brand" href="#!">Start Bootstrap</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"><span
          class="navbar-toggler-icon"></span></button>
      <div class="collapse navbar-collapse" id="navbarSupportedContent">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <router-link class="nav-link" active-class="active" to="/">Home</router-link>
          <router-link class="nav-link" active-class="active" to="/about">About</router-link>
          <router-link class="nav-link" active-class="active" to="/contact">Contact</router-link>
        </ul>
      </div>
    </div>
  </nav> -->
  <HeaderNav />
  <router-view :heading="heading" />
</template>
<style lang="scss">
@import '@/assets/css/main.scss';
@import 'https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css';
@import '@/assets/vendor/bootstrap-icons/bootstrap-icons.css';
@import '@/assets/vendor/swiper/swiper-bundle.min.css';
@import '@/assets/vendor/glightbox/css/glightbox.min.css';
@import '@/assets/vendor/aos/aos.css';
@import '@/assets/css/variables.css';
@import '@/assets/css/main.css';
</style>
<script>
import HeaderNav from '@/components/HeaderNav.vue';
export default {
  data() {
    return {
      heading: 'This is Heading Test',
    }
  },
  components: {
    HeaderNav
  }
}
</script>
