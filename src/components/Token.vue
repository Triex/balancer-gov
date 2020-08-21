<template>
  <img
    :src="
      `https://ropsten.rarible.com/static/d92a47dec5b1e2e530cd63f04fbdc7a3.png`
    "
    class="d-inline-block bg-gray-9 v-align-middle line-height-0 circle"
    :style="{
      width: `${size || 22}px`,
      height: `${size || 22}px`
    }"
  />
</template>

<script>
export default {
  props: ['address', 'size']
};
</script>
