<script>
import Vue from 'vue';
import DvImage from '@/dv-image.vue';

export default Vue.extend({
  name: 'ServeDev',
  components: {
    DvImage
  }
});
</script>

<template>
  <div id="app">
    <dv-image />
  </div>
</template>
