<template>
  <base-auth-layout>
    <center>
      <h1>Not Found!</h1>
      <p>
        <a href="/">Go home?</a>
      </p>
    </center>
  </base-auth-layout>
</template>

<script>

export default {
  name: 'NotFound'
}

</script>

<style scoped>

  center {
    margin: 15vw;
  }

  h1 {
    color: var(--border);
    font-size: 2em;
  }

</style>
