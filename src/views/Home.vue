<template>
  <div class="home">
    <h2>An embedded svg</h2>
    <div class="centered-image">
      <img alt="logo" src="../assets/mylogo.svg" class="logo">
    </div>
    <div class="centered-image">
      <logo-svg class="logo"></logo-svg>
    </div>
    <div class="centered-image">
      <logo-anim class="logo"></logo-anim>
    </div>
  </div>
</template>

<script>
import LogoSvg from '../components/LogoSvg.vue'
import LogoAnim from '../components/LogoAnim.vue'
export default {
  name: 'Home',
  components: {
    LogoSvg,
    LogoAnim
  }
}
</script>
<style>
.logo{
  width:200px;
  height:200px;
}
</style>
