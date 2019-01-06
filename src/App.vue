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
  html,body{
    padding: 0;
    margin: 0;
    font-size: 0;
  }
}
</style>
