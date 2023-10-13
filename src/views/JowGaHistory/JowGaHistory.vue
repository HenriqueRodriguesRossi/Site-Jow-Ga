<template>
  <section class="first-section">
    <div class="texts">
      <h2>O QUE É JOW-GA?</h2>

      <p>
        É um sistema tradicional de Kung Fu criado e desenvolvido pelo
        mestre Jow Lung, após experienciar e treinar 3 grandes estilos de
        Kung Fu: Hung Gar, Choy Gar (Choy Lay Fut) e Bak Sil Lam (Shaolin do
        Norte). Ele aprimorou as técnicas mais eficientes desses 3 estilos e
        os fundiu em um único lugar. Dssa junção resultou em um dos sistemas
        mais eficientes já criados, pelo grande arsenal de técnicas (tanto
        com mãos livres quanto com armas). Essa vastidão de técnicas permite
        que o Jow Ga seja absurdamente completo. Além de contar com as
        técnicas da luta mais antiga do mundo já registrada: Shuai Jiao
        (Shuai Jiao datava épocas de até 5 mil anos atrás. Era uma espécie
        de luta livre, que visava arremessar os inimigos ao chão seguido de
        golpes traumáticos). Com o tempo, shuai jiao foi sendo difundida e
        tornou-se parte de todos os estilos. Após Jow Lung desenvolver o
        estilo, voltou para sua terra natal, e na mesma época, estava
        acontecendo uma espécie de campeonato em nome do exército local
        contra 100 dos melhores mestres para decidir qual seria o estilo
        ensinado ao mesmo. Jow Lung foi o único a vencer todos os
        adversários, validando assim a eficiência do seu estilo e sendo
        consagrado o sistema com mais eficiência para autodefesa e foi
        responsável pela disseminação do estilo para o exercito. Pelo
        trabalho, entrega extrema e cansaço excessivo para lecionar seu
        estilo, Jow Lung morreu em 1919. Após sua morte, seu irmão, Jow Biu,
        assumiu o manto do estilo, renunciou seu cargo no exército e foi
        responsável pela boa parte da disseminação do Jow Ga na China. Até
        1935, mais de 80 escolas foram criadas para o ensino de Jow Ga Kuen.
        A escola de Hong Kong formou notáveis mestres, dentre eles o Lee
        Ngau. Lee Ngau treinou nosso mestre, Sam Hing Fai Chan; que por sua
        vez treinou Yakko Sideratos, que por sua vez, treinou por muito
        tempo, a mim, Felipe Reis, e estou prestes a treinar você.
      </p>
    </div>

    <div class="img">
      <img src="../../assets/JowLung.jpg" alt="Jow Lung - Criador do Jow Ga" @mouseover="showTooltip"
        @mouseleave="hideTooltip" />

      <div v-if="tooltipVisible" class="tooltip">
        <span class="description">Esse é Jow Lung, criador do Jow-Ga</span>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'JowGaHistory',

  data() {
    return {
      tooltipVisible: false,
    }
  },
  methods: {
    showTooltip() {
      this.tooltipVisible = true;
    },
    hideTooltip() {
      this.tooltipVisible = false;
    },
  }
}
</script>

<style scoped>
.first-section {
  padding-top: 50px;
  width: 100%;
  height: auto;
  display: flex;
  justify-content: space-around;
  align-items: center;
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

.first-section .texts {
  width: 600px;
  height: 600px;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.first-section h2 {
  color: gold;
  margin-bottom: 20px;
}

.first-section img {
  width: 600px;
  height: 500px;
}

p {
  color: ghostwhite;
  font-size: 16px;
}

.description{
  color: ghostwhite;
  font-size: 16px;
  width: auto;
  display: flex;
  justify-content: center;
}
</style>