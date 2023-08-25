<script setup>

</script>

<template>
<div>
    <button @click="createTodo">
    <slot>
      Create
    </slot>
    </button>

</div>

</template>

<style lang="scss" scoped>
  button {
    padding: 8px 16px;
    border: none;
  }

  </style>

