<template>
  <div class="home">
    <div class="container col-12 col-sm-6 col-lg-4">
      <bot-list />
    </div>
    <hr />
    <!-- <img alt="DropBot logo" src="../assets/freqtrade-logo.png" width="450px" class="my-5" /> -->
    <div alt="Dropbot logo" class="logo-svg my-5 mx-auto" />
  </div>
</template>

<script lang="ts">
import { defineComponent } from '@vue/composition-api';

import BotList from '@/components/BotList.vue';

export default defineComponent({
  name: 'Home',
  components: { BotList },
});
</script>

<style lang="scss" scoped>
.home {
  margin-top: 1.5em;
}
.logo-svg {
  background-image: url(../assets/dropbot.png);
  width: 250px;
  height: 250px;
  background-repeat: no-repeat;
  background-size: contain;
  background-color: #0000 !important;
}
</style>
