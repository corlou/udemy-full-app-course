<template>
  <q-page padding>
    <input v-model="message" />
    <button @click="message = ''">Clear</button>
    <h5>{{ message }}</h5>
  </q-page>
</template>

<script>
export default {
  data() {
    return {
      message: "I love vue.js so hard",
    };
  },
};
</script>

<style></style>
