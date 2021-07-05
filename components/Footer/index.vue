<template>
  <footer>
    <div class="chat">Chat</div>
    <div class="manifest">
      Top level domain name for sale from 7/18/2021 to present
    </div>
  </footer>
</template>

<style lang="scss" scoped>
footer {
  border-top: 1px solid white;
  display: flex;
  flex-direction: row;
  gap: 32px;
  text-shadow: 0px 2px 4px rgba(0, 0, 0, 0.2);
  padding-top: 16px;
}

.chat {
  font-weight: 600;
  font-size: 18px;
  line-height: 1.5;
  color: #ffffff;
  background-image: url(~assets/images/chat.svg);
  background-repeat: no-repeat;
  background-position: left center;
  padding-left: 24px;
  display: flex;
  flex-direction: row;
  align-items: center;
}

.manifest {
  font-weight: 600;
  font-size: 14px;
  line-height: 1.5;
  color: rgba(255, 255, 255, 0.5);
}
</style>
