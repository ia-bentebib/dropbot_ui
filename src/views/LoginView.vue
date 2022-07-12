<template>
  <div class="container">
    <b-card header="DropBot bot Login">
      <Login id="loginForm" ref="loginForm" />
    </b-card>
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';

import Login from '@/components/Login.vue';

export default defineComponent({
  name: 'LoginView',
  components: { Login },
});
</script>

<style scoped>
.container {
  max-width: 520px;
}
</style>
