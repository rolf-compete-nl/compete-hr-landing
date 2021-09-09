<template>
  <div>
    <Main />
    <p>Some text here!</p>
  </div>
</template>

<script>
import Main from './components/Main.vue'

export default {
  name: "App",
  components: {
    Main
  },
  data() {
    return {
      value: "World"
    };
  }
};
</script>
