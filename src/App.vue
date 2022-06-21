<!-- HTML --> 
<!-- Structure: Where does everything go? -->
<template>
  <h1 class="title">Tic Taco Toe</h1>
  <grid />
</template>

<!-- JavaScript --> 
<!-- Functionality: What does it do? -->
<script>
import Grid from './components/Grid.vue'
  
// Options API
export default {
  components: {
    'grid': Grid,
  },
  props: {},
  data() {
    return {
      values: [],
    }
  },
  computed: {},
  methods: {},
  mounted() {
  },
}
</script>

<!-- CSS --> 
<!-- Style: How does it look? -->
<style>
body {
  background-color: #FBFBFB;
}
#app {
  font-family: Roboto, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 28px;
  margin-top: 28px;
}
h1 {
  color: black;
  margin: 0;
}

</style>
