<template>
  <nav>
    <div class="container">
      <a class="card" href="mailto:info@cdmx.gay">
        <div class="content">
          <div class="operation">Transfer Domain Name</div>
          <div class="offer">
            <div class="name">cdmx.gay</div>
            <div class="price">$1,000.00 USD</div>
          </div>
        </div>
        <Button />
      </a>
      <div class="subline">Safely with ESCROW.COM</div>
    </div>
  </nav>
</template>

<style lang="scss" scoped>
.container {
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.card {
  background: linear-gradient(
      150deg,
      rgba(255, 255, 255, 0.2) 10%,
      rgba(0, 0, 0, 0) 80%
    ),
    #042e38;
  box-shadow: 0px 16px 14px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
  color: white;
  text-decoration: none;
}

.content {
  padding: 80px clamp(54px, 6vw, 80px) 54px;
  position: relative;
  display: flex;
  flex-direction: column;
}

.operation {
  position: absolute;
  left: 24px;
  top: 12px;
  font-size: clamp(14px, 1.5vw, 16px);
  line-height: 1.5;
  text-transform: uppercase;
  color: #b7e1eb;
  max-width: 8em;
}

.offer {
  text-align: center;
  display: flex;
  flex-direction: column;
}

.name {
  font-weight: bold;
  font-size: clamp(36px, 4.5vw, 54px);
  line-height: 1.5;
  color: #f4fdff;
  text-decoration: underline rgba(255, 255, 255, 0.25);
  text-underline-offset: 0.075em;
}

.price {
  font-family: 'Mogra', cursive;
  font-size: clamp(18px, 2vw, 24px);
  line-height: 1.2;
}

.subline {
  text-align: center;
  color: white;
  font-size: 12px;
  font-weight: 400;
  text-transform: uppercase;
}

@media (min-width: 720px) {
  .container {
    width: fit-content;
    margin-left: auto;
  }
}
</style>
