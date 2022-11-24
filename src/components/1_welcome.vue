<script>
export default ({
  name: 'Welcome',
  props: {
    label: {
      type: String,
      required: true,
    },
  },
});
</script>

<template>
  <div class="card">
    <h1>Bem-vindo {{ label }}</h1>
  </div>
</template>

<style scoped></style>
