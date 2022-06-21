<!-- HTML --> 
<!-- Structure: Where does everything go? -->
<template>
  <div class="grid">
    <grid-box/>
  </div>
</template>

<!-- JavaScript --> 
<!-- Functionality: What does it do? -->
<script>
import GridBox from './GridBox.vue'
import {getWinningLine} from '../winning.js'

export default {
  components: {
    'grid-box': GridBox
  },
  props: {
  },
  data() {
    return {
    }
  },
  methods: {
  },
  watch: {
  },
  mounted() {
  },
}

</script>

<!-- CSS --> 
<!-- Style: How does it look? -->
<style scoped>
.grid {
}
</style>