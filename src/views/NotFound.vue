<template>
  <div class="container">
    <h1>🍌</h1>
    <p class="title">404</p>
    <h1>Oh, no. Not here.</h1>
    <hr id="top-hr2" />
    <!-- <p class="not-found-container">You don't belong here.</p> -->
    <p>
      <img class="bg" src="./../assets/images/404.png" alt="404" />
      <router-link class="back-home" to="/">← Back home.</router-link>
    </p>
  </div>
</template>

<style scoped>
.not-found-container {
  margin: 240px 10;
}
.bg {
  width: 100%;
  margin-bottom: 40px;
  margin-top: -40px;
}

p {
  line-height: 30px;
}

.back-home {
  font-weight: bold;
  font-size: 18px;
}

.back-home:hover {
  border: none;
}

.title {
  font-weight: 700;
  /* font-weight: bold; */
  font-size: 68px;
  color: #000;
  margin: 40px;
}

#top-hr2 {
  width: 100px;
  margin: 30px auto;
  border-top: solid 3px #0070F3;
}

</style>
