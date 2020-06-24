<template>
  <div class="main">
    <div class="sub">
      <ProfilePic />
      <Heading />
    </div>

    <div class="sub">
      <Card />
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  margin: 0;
  padding: 0;
  background: #000000;
  overflow: hidden;
  font-family: "Poppins", sans-serif;
}
.main {
  width: 100vw;
  height: 100vh;
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-self: center;
  align-content: center;
  overflow: hidden;
}
.sub {
  display: flex;
  align-items:center;
  align-content: space-between;
  justify-content: space-around;
  padding: 10px;
}

@media screen and (max-width: 1000px) {
  .sub {
    flex-direction: column;
  }
}
</style>
