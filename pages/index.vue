<template>
  <div v-if="user==null">
    <LoginForm />
  </div>
</template>

<script>
export default {
  data: () => {
    return {
      user: null
    }
  }
}
</script>

<style>

</style>
