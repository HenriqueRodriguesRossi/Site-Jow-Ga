<template>
  <header class="header">
    <div class="header-text">
      <router-link to="/">
        <h1>Jow-Ga Brasil</h1>
      </router-link>
    </div>
    <div class="header-img">
      <img src="../assets/whatsApp-icon.png" alt="Botão para mandar mensagem no WhatsApp" @click="redirectsToWhatsapp" />
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',

  data() {
    return {
      phoneNumber: '11946075546'
    }
  },

  methods: {
    redirectsToWhatsapp() {
      const url = `https://api.whatsapp.com/send?phone=${this.phoneNumber}`;

      window.location.href = url;
    }
  }
}
</script>

<style scoped>
header {
  width: 100%;
  height: 100px;
  display: flex;
  justify-content: space-around;
  align-items: center;
  position: fixed;
  background-color: yellow;
  animation: fallAnimation 1s ease-out;
}

@keyframes fallAnimation {
  0% {
    opacity: 0;
    transform: translateX(+100%);
  }

  100% {
    opacity: 1;
    transform: translateX(0);
  }
}

header a {
  text-align: center;
  color: rgb(28, 28, 28);
  text-decoration: none;
  transition: all 0.5s;
}

header a:hover {
  color: ghostwhite;
  text-decoration: underline;
}

header img {
  width: 50px;
  height: 50px;
  cursor: pointer;
  transition: all 0.5s;
}

header img:hover {
  width: 60px;
  height: 60px;
}
</style>