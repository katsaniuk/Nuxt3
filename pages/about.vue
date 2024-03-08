<template>
  <div>
    <h2>About</h2>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus modi
      cumque corrupti rerum maxime libero ducimus nisi laborum minima labore.
    </p>
    <p>
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus modi
      cumque corrupti rerum maxime libero ducimus nisi laborum minima labore.
    </p>
    <div>{{ data }}</div>
  </div>
</template>

<script setup>
  const { data } = await useFetch('/api/currency/UAH');
</script>

<style scoped>
  h2 {
    margin-bottom: 20px;
    font-size: 36px;
  }
  p {
    margin: 20 0;
  }
</style>
