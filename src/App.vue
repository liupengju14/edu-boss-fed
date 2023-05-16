<template>
  <div id="app">
    <layout-aware>
      1
      <router-view/>
    </layout-aware>
  </div>
</template>
<script lang="ts">
import Vue from 'vue'
import layoutAware from './layout/index.vue'
export default Vue.extend({
  components: {
    layoutAware
  }
})
</script>
<style scope>
  #app {
    margin:0;
    padding:0;
    height:calc(100vh - 20px);
  }
</style>
