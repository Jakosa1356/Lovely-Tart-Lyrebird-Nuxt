<template>
  <div class="home-container"></div>
</template>

<script>
export default {
  name: 'Home',
  head: {
    title: 'Lovely Tart Lyrebird',
    meta: [
      {
        property: 'og:title',
        content: 'Lovely Tart Lyrebird',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
</style>
