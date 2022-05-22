<template>
  <div>
    <NuxtLink href="/">Home</NuxtLink> | <NuxtLink href="/test">Test</NuxtLink>
    <p>Hello {{ world }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      world: 'Test Page !!!!',
    };
  },
};
</script>
