<template>
  <section>
    <div>
      <h1 class="title">NUXT</h1>
      <h2 class="subtitle">Nuxt + SASS + Style Resources</h2>
      <h3 class="primary">This should be green!</h3>
    </div>
  </section>
</template>

<style lang="scss" scoped>
.title {
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
  display: block;
  font-weight: 400;
  font-size: 100px;
  color: #526488;
  letter-spacing: 1px;
  font-size: 6em;
}

.subtitle {
  font-weight: 300;
  font-size: 3em;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.primary {
  color: $primary;
}
</style>
