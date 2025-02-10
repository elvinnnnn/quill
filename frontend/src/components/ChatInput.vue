<script setup lang="ts">
defineOptions({
  name: "ChatInput",
});
</script>

<template>
  <input type="text" placeholder="Message @user" />
</template>

<style scoped>
input {
  width: 80%;
  height: 5%;
}
</style>
