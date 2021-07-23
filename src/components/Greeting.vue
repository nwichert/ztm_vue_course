<template>
  <p v-if="age > 25">{{msg}}</p>
  <p v-else>You must be 25 years or older to view this message.</p>
</template>

<script>
export default {
  name: "Greeting",
  props: ['age'],
  data() {
    return {
      msg: "Welcome to the dark web!",
    };
  },
};
</script>

<style scoped>
p {
  color: red;
}
</style>