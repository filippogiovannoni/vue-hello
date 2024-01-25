<script>
export default {
  name: 'App',
  data() {
    return {
      message: 'Hello Vue!',
      image: 'https://picsum.photos/400/300',
    }
  }
}
</script>

<template>
  <h1>
    {{ message }}
  </h1>

  <img v-bind:src="image" alt="">
</template>

<style></style>