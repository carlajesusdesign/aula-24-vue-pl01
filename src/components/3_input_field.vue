<template>
  <div>
    <h1>{{ inputTextValue }}</h1>
    <input type="text" v-model="inputTextValue" />
  </div>
</template>

<script>
export default {
  name: 'InputField',
  data() {
    return {
      inputTextValue: ''
    },
  },

};
</script>

<style scoped></style>
