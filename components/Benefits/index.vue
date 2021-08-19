<template>
  <section>
    <ul lang="es">
      <li>Corto</li>
      <li>Cautivador</li>
      <li>Memorable</li>
      <li>Transferencia segura</li>
    </ul>
  </section>
</template>

<style lang="scss" scoped>
section {
  padding: 24px;
}

ul {
  list-style-type: none;
}

li {
  background-image: url(~assets/images/marker.svg);
  background-repeat: no-repeat;
  background-position: center left;
  padding-left: clamp(1.5rem, 2vw, 3rem);
  font-style: normal;
  font-weight: 600;
  font-size: clamp(1.25rem, 2vw, 2rem);
  line-height: 1.6;
  color: white;
  text-shadow: 0 0 4px rgba(0, 0, 0, 0.5);
}

@media (min-width: 720px) {
  section {
    padding: 12px 42px;
    padding-left: 0;
  }
}
</style>
