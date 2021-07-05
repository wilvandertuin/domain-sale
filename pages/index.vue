<template>
  <div class="layout">
    <Logo />
    <main>
      <C2a />
      <Benefits />
    </main>
    <Footer />
  </div>
</template>

<style lang="scss" scoped>
.layout {
  display: flex;
  flex-direction: column;
  margin: 0 auto;
  height: 100%;
  min-height: 100%;
}

@media (max-width: 719px) {
  .layout {
    max-width: 360px;
    row-gap: 36px;
    justify-content: space-between;
  }

  main {
    display: contents;
  }
}

@media (min-width: 720px) {
  .layout {
    display: flex;
    width: 100%;
    max-width: 800px;
    row-gap: 60px;
  }

  main {
    // display: flex;
    // flex-direction: row;
    // column-gap: 32px;
    // justify-content: center;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    column-gap: 32px;
  }
}
</style>
