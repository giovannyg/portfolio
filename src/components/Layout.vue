<template>
  <div id="layout">
    <top-nav />
    <div id="content">
      <img alt="Vue logo" src="../assets/logo.png" style="margin: 0 auto; display: block" />
      <router-view></router-view>
    </div>
    <footer id="wide_screen_footer">
      <div id="wide_screen_footer_content">
        &copy; Giovanny González
      </div>
    </footer>
  </div>
</template>

<script>

import TopNav from './TopNav.vue';

export default {
  components: {
    TopNav
  }
}
</script>