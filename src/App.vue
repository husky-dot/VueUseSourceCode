// MyComponent.vue
<template>
  <div>
    <h1>计数器：{{ count }}</h1>
    <button @click="increment">增加</button>
    <button @click="decrement">减少</button>
  </div>
</template>

<script lang="ts" setup>
import { useGlobalState } from "./store";

const { count } = useGlobalState();

const increment = () => {
  count.value++;
};

const decrement = () => {
  count.value--;
};
</script>
