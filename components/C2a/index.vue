<template>
  <nav>
    <div class="container">
      <a class="card" href="#">
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
      148.91deg,
      rgba(255, 255, 255, 0.2) 10.24%,
      rgba(0, 0, 0, 0) 79.89%
    ),
    #042e38;
  box-shadow: 0px 16px 14px rgba(0, 0, 0, 0.2);
  border-radius: 8px;
  color: white;
  text-decoration: none;
}

.content {
  padding: 80px 18px 54px;
  position: relative;
  display: flex;
  flex-direction: column;
}

.operation {
  position: absolute;
  left: 24px;
  top: 12px;
  font-size: 14px;
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
  font-size: 36px;
  line-height: 1.5;
  color: #f4fdff;
  text-decoration: underline rgba(255, 255, 255, 0.25);
  text-underline-offset: 0.075em;
}

.price {
  font-family: 'Mogra', cursive;
  font-size: 18px;
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
  nav {
  }

  .container {
    width: 280px;
    margin: 0 auto;
  }
}
</style>
