<template>
  <img src="/0.jpeg" class="Pic" />
</template>

<style>
.Pic {
  border-radius: 100%;
  width: auto;
  max-width: 400px;
  max-height: 400px;
  height: auto;
  animation: 1s appear;
  margin: auto;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
}

@media screen and (max-width: 1000px) {
  .Pic {
    max-width: 200px;
    max-height: 200px;
  }
}
</style>
