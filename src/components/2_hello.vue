<script>
export default {
  name: 'Welcome',
  props: {
    label: {
      type: String,
      required: true,
    },
  },
};

var today = new Date();
var curHr = today.getHours();

if (curHr < 12) {
  console.log('good morning');
} else if (curHr < 18) {
  console.log('good afternoon');
} else {
  console.log('good evening');
}
</script>

<template>
  <div class="card">
    <h1>Bem-vindo {{ label }}</h1>
  </div>
</template>

<style scoped></style>
