<script setup lang="ts">
import RootComponent from './RootComponent.vue'
import CountComponent from './CountComponent.vue'
import ButtonComponent from './ButtonComponent.vue'
</script>

<template>
  <div>
    <RootComponent>
      <ButtonComponent />
      <CountComponent />
    </RootComponent>
  </div>
</template>
