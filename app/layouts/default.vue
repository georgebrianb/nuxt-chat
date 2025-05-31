<template>
  <div class="layout-container">
    <main class="main-content">
      <slot />
    </main>
  </div>
</template>

<script lang="ts" setup></script>

<style scoped>
.layout-container {
  height: calc(100vh - 4rem);
  background-color: #f0f0f0;
}

.main-content {
  height: 100%;
  margin-top: 4rem;
}
</style>
