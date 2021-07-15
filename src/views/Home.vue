<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <p>开始学习vue3</p>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from 'vue-class-component';

@Options({
  components: {
  },
})
export default class Home extends Vue {}
</script>
