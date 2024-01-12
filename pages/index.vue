<template>
  <div class="home">
    <h1>{{ "message" }}</h1>
    <p>Welcome to my responsive Nuxt.js website!</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@nuxt/vue-app';

export default defineComponent({
  data() {
    return {
      message: 'Hello, Nuxt.js with TypeScript!',
    };
  },
});
</script>

<style scoped>
.home {
  text-align: center;
  padding: 20px;
}

@media (max-width: 600px) {
  .home {
    font-size: 14px;
  }
}
</style>