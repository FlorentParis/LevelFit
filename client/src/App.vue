<script setup lang="ts">
import { RouterView } from 'vue-router';
import NavbarLeft from '@/components/organisms/NavbarLeft/index.vue';
import LayoutContainer from '@/components/organisms/LayoutContainer/index.vue';
</script>

<template>
  <LayoutContainer>
    <NavbarLeft />
    <RouterView />
  </LayoutContainer>
</template>
