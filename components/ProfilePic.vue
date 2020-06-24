<template>
  <div class="img">
    <img src="/0.jpeg" class="Pic" />
  </div>
</template>

<style>
.Pic {
  vertical-align: middle;
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
</style>
