<template>
  <div class="home">
    <SliderComps :msg="cardtext" :imageUrl="image" />
  </div>
</template>

<script lang="ts">
import SliderComps from '@/components/SliderComps.vue';
export default {
  props: ['heading'],
  data() {
    return {
      cardtext: 'This is Home Page Text',
      image: 'https://media.geeksforgeeks.org/wp-content/cdn-uploads/20220505001016/5-Vue.Js-Advantages-That-Every-Developer-Must-Know.jpg'
    }
  },
  components: {
    SliderComps,
  },
}
</script>
