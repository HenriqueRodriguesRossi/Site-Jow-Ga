<template>
    <section>
        <h2>OTIMIZANDO O FOCO</h2>
        <div class="section-texts">
            <p>Até agora você viu que realmente vai aprender bastante coisa, são muitas vertentes que um único sistema
                ensina. E eu, como seu instrutor, faço o seguinte esquema para cumprir minha promessa a você para resultados
                exponenciais:</p>

            <ul>
                <li>- Treinamos uma vertente de cada vez, a fundo, com validação no final.</li>
                <li>- 1 mês inteiro (8 aulas), estudamos e treinamos exaustivamente cada vertente de combate que o sistema
                    possui e ensina.</li>
                <li>- Estudamos separadamente membros superiores, membros inferiores, energia, quedas e projeções, armas e
                    mais 3 aulas especiais.</li>
                <li>- Dessa forma, você acelera seus aprendizados e afia suas ferramentas de uma forma mais rápida e
                    eficiente.</li>
                <li>- Em cada vertente, exploramos e treinamos absolutamente TUDO o que dá para usar na autodefesa. Membros
                    superiores são muito mais do que só socos e cotovelos; inferiores, são muito mais do que chutes e
                    joelhadas. Literalmente, explorar todo o corpo para usá-lo em prol da sua integridade, caso seja preciso
                    e transformá-lo numa arma afiada de todos os ângulos.</li>

                <li>-Esses estudos acontecem na etapa de “conhecimentos gerais”, e se complementam na etapa de “Conteúdos de
                    faixa” de cada aula.</li>
            </ul>
        </div>
    </section>
</template>

<script>
export default {
    name: 'OptimizingFocus'
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
    width: auto;
    height: auto;
    text-align: center;
    font-weight: 500;
    margin-top: 30px;
}

ul {
    padding: 30px 150px;
    list-style: none;
    display: flex;
    flex-direction: column;
    gap: 20px;
    justify-content: center;
    align-items: center;
    font-weight: 600;
}

@media(max-width: 600px){
    h2{
        margin-top: -120px;
    }

    .section-texts{
        width: 400px;
        height: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 5px;
    }

    .section-texts ul li{
        width: 400px;
        height: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 10px;
        text-align: center;
    }
}
</style>