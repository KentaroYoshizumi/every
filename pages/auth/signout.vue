<template>
  <h1>Signout</h1>
</template>

<script>
export default {
  asyncData() {
    $nuxt.$fire.auth.signOut();
  },
};
</script>
