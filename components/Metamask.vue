<template>
  <v-btn
    color="blue"
    class="d-flex flex-row align-center"
    @click="$emit('connect')"
  >
    <img
      src="https://upload.wikimedia.org/wikipedia/commons/3/36/MetaMask_Fox.svg"
      alt="Metamask"
      height="20"
      class="mr-2"
    />
    Connect to Metamask
  </v-btn>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
