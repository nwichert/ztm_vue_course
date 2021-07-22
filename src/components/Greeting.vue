<template>
  <p>Hello, {{name}}!</p>
</template>

<script>
export default {
  name: "Greeting",
  data() {
    return {
      name: "Nick"
    }
  }
}
</script>

<style scoped>
p {
  color: red;
}
</style>