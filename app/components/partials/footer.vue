<template>
  <footer class="footer -mx-4 md:mx-0">
    <div class="container mx-auto pb-6 flex justify-center">
      <a href="https://www.dropbox.com/s/21mpc5j5hs97y4p/app-release.apk?dl=1">
        Download APK
      </a>
    </div>
  </footer>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator';

@Component
export default class Footer extends Vue {}
</script>

<style lang="scss">
.footer {
  background-color: $bluise;
  a {
    color: #f7f8fb;
  }
}
</style>
