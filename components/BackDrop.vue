<template>
  <div>
    <div class="stars"></div>
    <div class="twinkling"></div>
  </div>
</template>

<style>
div {
  margin: 0;
  padding: 0;
}

/* background animation */
@keyframes move-twink-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -10000px 5000px;
  }
}

@keyframes move-twink-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -10000px 5000px;
  }
}

@keyframes move-twink-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -10000px 5000px;
  }
}

@keyframes move-twink-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: -10000px 5000px;
  }
}

@keyframes move-clouds-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: 10000px 0;
  }
}

@keyframes move-clouds-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: 10000px 0;
  }
}

@keyframes move-clouds-back {
  from {
    background-position: 0 0;
  }

  to {
    background-position: 10000px 0;
  }
}

@keyframes move-clouds-back {
  from {
    background-position: 0;
  }

  to {
    background-position: 10000px 0;
  }
}

.stars,
.twinkling {
  position: absolute;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  width: 100%;
  height: 100%;
  display: block;
}

.stars {
  background: transparent url("/stars.png") repeat top center;
  z-index: 0;
}

.twinkling {
  background: transparent url("/twinkling.png") repeat;
  top: center;
  z-index: 0;
  -moz-animation: move-twink-back 200s linear infinite;
  -ms-animation: move-twink-back 200s linear infinite;
  -o-animation: move-twink-back 200s linear infinite;
  -webkit-animation: move-twink-back 200s linear infinite;
  animation: move-twink-back 200s linear infinite;
}
</style>