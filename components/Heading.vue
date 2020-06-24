<template>
  <h1>
    {{name}}
  </h1>
</template>

<script>
export default {
  data() {
    return {
      name: "Akshara S Nair"
    };
  }
};
</script>
<style scoped>
h1 {
  color: #ffffff;
  font-size: 10rem;
  line-height: 1;
  font-weight: bold;
  letter-spacing: 2px;
}

@media screen and (max-width: 1000px) {
  h1 {
    margin-top: 3rem;
    font-size: 2.8rem;
  }
}
</style>