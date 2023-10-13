<template>
    <h2>SUA FORMA DE LUTAR</h2>
    <section>
        <div class="section-img">
            <img src="../../assets/imagemFelipe01.jpg" alt="Imagem do professor treinando" width="600" height="600"
                @mouseover="showTooltip" @mouseleave="hideTooltip">

            <div v-if="tooltipVisible" class="tooltip">
                <span class="description">Esse sou eu (Felipe), o seu instrutor daqui para frente!</span>
            </div>
        </div>

        <div class="section-texts">
            <p>Como eu já havia dito, o sistema utiliza de um belo arsenal de técnicas, visando garantir sua integridade em
                todas e quaisquer circunstâncias.
            </p>

            <p>Você vai ver em aula que o sistema preza a eficiência, ou seja, se funciona e
                preserva sua vida, é válido. Mas as técnicas e os movimentos têm suas características: </p>

            <ul>
                <li>-Defesa e ataques simultâneos </li>

                <li>-Quadril como principal vetor de potência</li>

                <li>-Chutes rápidos</li>
            </ul>

            <p>Além da característica de combate com:</p>
            <ul>
                <li>- Torções</li>
                <li>- Quedas e projeções- Shuai Jiao (Judô Chinês)</li>
                <li>- Técnicas dos renomados 5 animais (serpente, tigre, garça, leopardo e Louva-Deus).</li>
                <li>- Jow Ga vai utilizar a potência do Hung gar, destreza do Choy Gar e footwork do Bak Sil Lam.</li>
            </ul>
        </div>

    </section>
</template>

<script>
export default {
    name: "WayToFight",

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
h2 {
    color: gold;
    padding-top: 50px;
    text-align: center;
    margin-bottom: 40px;
    margin-top: 50px;
    font-size: 30px;
}

section {
    width: auto;
    height: auto;
    display: flex;
    justify-content: space-around;
    color: ghostwhite;
    font-size: 16px;
    text-align: center;
    margin-bottom: 50px;
}

.section-texts {
    width: 600px;
    height: 600px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

ul {
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: center;
    align-items: center;
    font-weight: 600;
}
</style>