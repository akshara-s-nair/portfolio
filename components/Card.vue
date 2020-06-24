<template>
  <div class="card">
    <p class="text">Connect me via</p>
    <div class="icons">
      <a href="https://github.com/akshara-s-nair/">
        <font-awesome-icon :icon="['fab', 'github']" />
      </a>
      <a href="https://www.linkedin.com/in/akshara-s-nair-8319161aa/">
        <font-awesome-icon :icon="['fab', 'linkedin']" />
      </a>
    </div>
  </div>
</template>

<style scoped>
.card {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 2vmax;
  border-radius: 20px;
  font-size: 3rem;
  color: #ffffff;
  margin-top: 5vh;
}

.icons a {
  text-decoration: none;
  font-size: 4vmax;
  color: #ffffff;
  padding: 2rem;
}

@media screen and (max-width: 1000px) {
  .card {
    padding: 10vmax;
    font-size: 1.6rem;
  }

  .icons a {
    padding: 2vmin;
  }
}
</style>