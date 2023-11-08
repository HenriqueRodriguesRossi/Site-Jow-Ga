<template>
    <section>
        <h2>POR QUÊ TREINAR JOW GA?</h2>
        <p>A resposta para essa pergunta, no fundo, tem que vir de você, caro aluno. Quais são os seus objetivos? para o que
            quer aprender uma arte marcial tão poderosa? Apesar de a resposta pra isso deva vir de você, os treinos têm seus
            inúmeros benefícios:</p>

        <ul>
            <li>
                -	De cara, você vai desenvolver mais segurança para andar na rua. Pois saberá que tem capacidade de se defender, independente da circunstância e do agressor. (E não me refiro somente a saber desferir golpes, hein?)
            </li>

            <li>
                -	Vai desenvolver mais saúde, resistência, flexibilidade, longevidade, coordenação motora, memória, reflexo, disciplina, foco e mais uma caralhada de coisa.
            </li>

            <li>
                -	É um estilo perfeito para quem quer ter em um equilíbrio perfeito na convivência entre a tradicionalidade do kung-fu, ainda mais de 3 grandes estilos,um deles um dos mais antigos já registrados: Bak Sil Lam (shaolin do norte), e as adaptações para os dias de hoje, e desmistificar que kung fu não funciona para auto-defesa.
            </li>

            <li>
                -	Dito os 3 estilos que compõem o Jow Ga; você terá acesso às técnicas mais eficientes e aprimoradas de grandes estilos marciais, em um único lugar.
            </li>
        </ul>
    </section>
</template>

<script>
export default {
    name: "WhyTrainJowGa"
}
</script>

<style scoped>
section {
    padding-top: 50px;
    width: auto;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: ghostwhite;
    font-size: 16px;
}

h2 {
    color: gold;
    padding-top: 50px;
    text-align: center;
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
    margin-top: 20px;
}

ul{
    text-align: center;
    text-decoration: none;
    margin-top: 10px;
}

@media(max-width: 600px){
    section{
        margin-top: -70px;
    }

    p{
        width: 100%;
        height: auto;
        text-align: center;
    }
    
    ul li{
        width: 400px;
        height: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
    }
}
</style>