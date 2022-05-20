<template>
  <div>{{ userStore.name }}</div>
</template>

<script setup>
  import { useUserStore } from '@/store/modules/user'

  const userStore = useUserStore()
  userStore.updateName('李四')
</script>
