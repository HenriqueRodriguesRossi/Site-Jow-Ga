<template>
    <h2 class="h2">CONHEÇA SEU INSTRUTOR</h2>

    <p class="p">
        Fala, aluno, beleza? Muito prazer. Você viu logo acima que treinar comigo tem seus diferenciais, e quero
        aproveitar e permitir que você conheça um pouco mais sobre mim, ainda mais, porque, seremos família quando
        entrar pra nossa turma.
        Me chamo Felipe Reis, eu tenho 23 anos e já treino kung fu há 20 anos. Desde pequeno eu tive muita energia para
        gastar e a saída que minha mãe encontrou foi me colocar em algum esporte. Comecei no judô, mas minha mãe conta
        que eu não gostei muito (bom, eu não lembro, mas é engraçado pensar, ainda mais que ensino shuai jiao nas
        aulas). Depois do judô, meu pai achou uma rede de academia do estilo louva deus, e eu lembro de só ter aceitado
        treinar lá, porque o professor na época me prometeu a fazer um jutsu do Naruto (me dá um desconto, eu só tinha 3
        ou 4 anos) e eu adorava Naruto. Eu não lembro muito dessa academia; mas tenho a foto da minha 1ª aula até hoje,
        se liga só:
    </p>

    <section class="section">
        <div class="imgs">
            <div class="img">
                <img src="../../assets/littleFelipe.jpg" alt="Imagem do primeiro treino do professor"> <br>

                <span class="description-span">Eu indo para a 1ª aula nos meus 3 ou 4 aninhos hahah</span>
            </div>

            <div class="img">
                <img src="../../assets/faixas.jpg" alt="Imagem das faixas do professor"> <br>

                <span class="description-span">Essas aqui são as minhas faixas de quando treinei lá</span>
            </div>

            <p class="p">
                Eu treinei nessa academia até os meus 10 anos. Depois que saí, não lembro de ter ficado muito tempo parado,
                pois no início de 2011 mesmo eu entrei na academia que estou até hoje e inclusive é onde você terá aulas
                comigo. Desde 2011 eu treino o estilo Jow Ga, e nesses 12 anos treinando muita coisa aconteceu, muitas
                histórias, muitos acontecimentos; uns bons, outros ruins. Todos esses acontecimentos são livro aberto
                comigo, mas como são muitos para descrever aqui, você vai ficar sabendo no decorrer das aulas quando eu
                compartilho com a turma. Mas, um dos mais marcantes para mim nesses anos foram quando durante 5 anos, na
                minha adolescência, enfrentei a depressão, ansiedade, culpa e angústia. Anos esses que bem quando eu poderia
                estar num auge, eu acabei desistindo de tudo o que me fazia bem. E a real é que, na época, música, a
                hipnoterapia e o kung fu, salvaram muito a minha vida. De uma forma resumida, dentre tantas coisas que eu
                vivi, mesmo com pouca idade, que desde 2021 eu assumi a responsabilidade de ministrar uma turma e entrego
                tudo de mim por ela. Nossas aulas são a minha vitória, e é impressionante o quanto eu amo estar na frente da
                turma para poder ensinar, divertir, evoluir, conectar; arrisco-me a dizer que as nossas aulas são meu bem
                mais valioso, e não abro mão delas por absolutamente nada. E outra coisa muito incrível: quando entrar para
                nossa turma, você fará parte da única família que representa o Jow Ga Kung Fu aqui no Brasil e na América
                Latina, praticamente. Só isso é uma experiência absurda.
                Okay, acho que já falei o bastante de mim até aqui, e está na hora de você ver na prática como é que eu
                impacto a vida de todos os meus alunos nas nossas aulas, vou deixar aqui abaixo alguns depoimentos. veja
                pelo depoimento dos alunos.

            </p>
        </div>
    </section>
</template>

<script>
export default {
    name: "MeetYourInstructor"
}
</script>

<style scoped>
.h2 {
    color: gold;
    margin-bottom: 20px;
    text-align: center;
    font-size: 30px;
    margin-top: 50px;
}

p {
    color: ghostwhite;
    font-size: 16px;
    font-weight: 500;
    padding-left: 50px;
    padding-right: 50px;
    width: auto;
    text-align: center;
}

section {
    padding-top: 50px;
    width: 100%;
    height: auto;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-direction: row;
}

.imgs {
    width: auto;
    height: auto;
    display: flex;
    justify-content: space-around;
    align-items: center;
    flex-wrap: wrap;
    gap: 20px;
}

.img img {
    width: 600px;
    height: 600px;

}

.description-span {
    width: auto;
    color: ghostwhite;
    font-size: 16px;
    font-weight: 700;
    text-align: center;
    display: flex;
    justify-content: center;
    margin-top: 10px;
}

.p {
    margin-top: 15px;
}

@media(max-width: 600px) {
    h2 {
        margin-top: -70px;
    }

    .p {
        width: 100%;
        height: auto;
        text-align: center;
    }

    .section {
        width: 100%;
        height: auto;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .section .img img {
        display: flex;
        gap: 10px;
        width: 400px;
        height: 400px;
    }
    .description-span{
        width: auto;
        display: flex;
        justify-content: center;
        align-items: center;
    }
}
</style>