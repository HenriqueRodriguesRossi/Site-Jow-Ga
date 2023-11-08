<template>
    <section>
        <h2>A BASE DE TUDO</h2>

        <p>
            Jow Ga é um estilo tradicional chinês de Kung Fu, e tudo o que treinamos são baseados nos conceitos usados para
            criar esse estilo, por isso treinamos e também estudamos os Taolus. E ao contrário do que muita gente pensa,
            Taolus são uma parte importante do treinamento.
        </p>

        <ul>
            <li>
                - Taolus são técnicas de combate coreografadas para você treinar sozinho.
            </li>

            <li>
                - Servem para o foco principal, entendimento de técnicas básicas; e a estratégia vem depois
            </li>

            <li>
                - Se você não possui uma estrutura sólida para construir seu arsenal de técnicas, você fica incapaz de
                utilizar com máxima eficiência o que aprende e acaba se tornando inútil e sem energia de impacto, caso
                precise usar numa circunstância real.
            </li>

            <li>
                - Ajudam a desenvolver timing, amplitude, força, energia, resistência, velocidade e equilíbrio.
            </li>

            <li>
                - O sistema conta com mais de 20 taolus de mãos vazias e mais de 18 com armas. Sendo elas treinadas sozinho
                ou em dupla.
            </li>

            <li>
                - Cada técnica dos taolus serão estudadas e treinadas; pois sem entendimento do que elas são e o que as
                compõem, os taolus se tornam nada mais do que uma dança atrativa.
            </li>

            <li>
                - E sem praticar as técnicas de combate, você acaba se tornando incapaz de utilizar o que vai ver em aula
                numa circunstância real.
            </li>
        </ul>
    </section>
</template>

<script>
export default {
    name: "BaseOfEverything"
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
    section h2{
        margin-top: -20px;
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