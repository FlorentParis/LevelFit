<template>
  <div class="layout-container">
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'LayoutContainer',
});
</script>

<style src="./style.scss" lang="scss"></style>
