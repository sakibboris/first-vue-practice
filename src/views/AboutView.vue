<template>
  <div class="about">
    <SliderComps :msg="cardtext" :imageUrl="image" />
  </div>
</template>
<script>
import SliderComps from '@/components/SliderComps.vue';
export default {
  data() {
    return {
      cardtext: 'This is About Page Text',
      image: 'https://blog.vueschool.io/wp-content/uploads/2023/02/Vue.js-Certification-Program-Launched.jpg'
    }
  },
  components: {
    SliderComps
  }
}
</script>