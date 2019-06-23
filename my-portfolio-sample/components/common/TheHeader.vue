<template>
<header class="header">
<div class="header-inner">
    <h1>my-portfolio</h1>
    自己紹介
  </div>
</header>
</template>
<style scoped lang="scss">
  // @nuxtjs/style-resourcesプラグインインストール後にnuxt.config.js|modules・styleResources内に記述したことにより不要になった
  // @import "~assets/scss/variables";

  .header {
    background-color: $color-gray;
  }

  .header-inner {
    height: 60px;
    max-width: 600px;
    margin: 0 auto;
    display: flex;
    align-items: center;
    justify-content: space-between;

    a {
      color: inherit;
    }
  }
</style>