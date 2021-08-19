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
  display: flex;
  flex-direction: column;
  gap: 8px;
}

li {
  background-image: url(~assets/images/marker.svg);
  background-repeat: no-repeat;
  background-position: center left;
  padding-left: 24px;
  font-style: normal;
  font-weight: 600;
  font-size: 20px;
  line-height: 1.25;
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
