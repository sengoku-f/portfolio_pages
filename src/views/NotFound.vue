<template>
  <div class="container">
    <h1>🍌</h1>
    <h1>404</h1>
    <h1>Oh, no. Not here.</h1>
    <hr id="top-hr" />
    <p class="not-found-container">You don't belong here.</p>
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
</style>
