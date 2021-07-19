<template>
  <figure>
    <nuxt-picture
      fit="cover"
      format="webp"
      quality="100"
      provider="static"
      src="/images/teddy-osterblom-owiVf9bFKHM-unsplash.jpg"
    />
  </figure>
</template>

<style lang="scss" scoped>
figure {
  position: fixed;
  inset: 0;
  margin: 0;
  padding: 0;
  z-index: -1;
}

::v-deep img {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

figure::after {
  content: '';
  position: absolute;
  inset: 0;
  background: linear-gradient(
      180deg,
      rgba(0, 0, 0, 0) 0%,
      rgba(82, 33, 6, 0.79) 80%,
      rgba(82, 33, 6, 0.79) 100%
    )
    bottom left no-repeat;
  background-size: cover;
}
</style>
