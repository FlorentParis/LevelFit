<template>
  <div class="navbar-left">
    <router-link to="/">Accueil</router-link>
    <router-link to="/page1">Page 1</router-link>
    <router-link to="/page2">Page 2</router-link>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'NavbarLeft',
});
</script>

<style src="./style.scss" lang="scss"></style>
