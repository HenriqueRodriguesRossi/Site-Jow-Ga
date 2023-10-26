<template>
    <h2>AFIAÇÃO VALIDADA</h2>

    <p>Absolutamente tudo o que você aprender e treinar será colocado à prova de validação.Mais importante do que as
        características das técnicas, dos movimentos e etc, é a forma como você as utilizará para sua vida. A rua
        não é um campeonato, rua não é ringue, na rua é vida por vida e a função da sua autodefesa é preservá-la a
        qualquer custo. O sistema Jow Ga se adequa a você, e não você ao sistema. Por essa razão que apanhamos na
        academia, para não apanharmos na rua:</p>

    <section>
        <div class="section-texts">
            <ul>
                <li>
                    - Faremos sparrings frequentes (voltado para sua integridade)

                </li>

                <li>
                    - No final de cada vertente estudada, fazemos a “sobrevivência modular”, onde faremos uma luta em que
                    você só poderá usar a região que foi treinada naquele mês, ou seja, só poderá usar membros superiores,
                    ou inferiores, ou só energia, ou só quedas e projeções ou, e sim, somente armas.
                </li>

                <li>
                    - Dessa forma você induz seu cérebro a criar mecanismos de defesa, induz ele arranjar formas de
                    compensar o que não vai poder usar; ou seja, se defender com o que tem ( preservar a vida a qualquer
                    custo).
                </li>

                <li>
                    - Fazemos isso porque é assim que pode acontecer na rua, você não sabe onde, quando ou como vai ser
                    atacado; pode ser que você esteja livre e possa usar o corpo todo, mas você tem que manter tudo afiado
                    para se caso precise, você consiga se garantir usando só uma ou outra vertente.
                </li>

                <li>
                    - No final de cada ciclo, fazemos nossa sobrevivência geral: aí, sim é o dia que pode usar todas as
                    vertentes que treinamos aos longos dos meses e colocar em prática tudo o que validou nas sobrevivências
                    modulares
                </li>

                <li>
                    - São com esses treinos que você vai sentindo o que funciona para você e como ter o máximo de resultado
                    com isso.
                </li>
            </ul>
        </div>

        <div class="section-img">
            <img src="../../assets/imagem-felipe-02.jpg" alt="Imagem do professor lutando">
        </div>
    </section>
</template>

<script>
export default {
    name: "ValidatedSharpening"
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

p {
    color: ghostwhite;
    font-size: 16px;
    width: auto;
    height: auto;
    text-align: center;
    padding-left: 50px;
    padding-right: 50px;
}

section {
    padding-top: 50px;
    width: 100%;
    height: auto;
    display: flex;
    justify-content: space-around;
    align-items: center;
}

.section-img,
.section-texts {
    width: 50%;
    height: auto;
}

ul {
    list-style: none;
    font-size: 16px;
    color: ghostwhite;
}

img {
    width: 600px;
    height: 650px;
}

@media(max-width: 600px){
    h2{
        margin-top: -20px;
    }

    section, .section-texts ul li{
        width: 400px;
        height: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
    }

    .section-texts ul{
        margin-top: -15px;
    }
}
</style>