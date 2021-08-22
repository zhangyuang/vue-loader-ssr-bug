
<template>
  <div>
    <div class="$style.app">
      213
    </div>
  </div>
</template>

<script lang="ts">

export default {
  created () {
    console.log(this.$style)
  }
}
</script>

<style module>
.app {
  color: red
}
</style>
