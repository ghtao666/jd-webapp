<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: "App"
};
</script>

<style lang="less">
#app {
  max-width: 750PX; //大写PX
  margin: 0 auto;

  .clearfix {
    overflow: auto;
    _height: 1%;
  }
}
</style>
