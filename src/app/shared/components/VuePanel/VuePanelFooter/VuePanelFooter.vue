<template>
  <div :class="['vue-panel-footer', $style.vuePanelFooter]">
    <slot />
  </div>
</template>

<script lang="ts">
  export default {
    name: 'VuePanelFooter',
    components: {},
    props: {},
    data: function () {
      return {};
    },
    computed: {},
    methods: {},
  };
</script>

<style lang="scss" module>
  @import "../../../styles";

  .vuePanelFooter {
    display: block;
    padding: $panel-footer-padding;
  }
</style>
