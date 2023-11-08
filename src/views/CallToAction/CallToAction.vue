<template>
  <div class="finished">
    <h2>QUER COMEÇAR A TREINAR?</h2>
    <h2>PRECISA DE MAIS INFORMAÇÕES?</h2>
    <button @click="redirectsToWhatsapp">ME CHAME NO WHATSAPP</button>
  </div>
</template>

<script>
export default {
  name: "CallToAction",

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
.finished{
  width: auto;
  height: auto;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

h2{
  color: gold;
  font-size: 30px;
  width: auto;
  text-align: center;
  margin-top: 50px;
}

button {
  background-color: rgb(15, 157, 88);
  color: ghostwhite;
  border: 2px solid ghostwhite;
  font-size: 16px;
  border-radius: 20px;
  width: 300px;
  height: 40px;
  cursor: pointer;
  transition: all 1s;
  animation: pulse 1.5s infinite;
  margin-top: 30px;
  margin-bottom: 50px;
}

@keyframes pulse {
  0% {
    transform: scale(1);
  }

  50% {
    transform: scale(1.2);
  }

  100% {
    transform: scale(1);
  }
}


button:hover {
  animation: none;
}
</style>