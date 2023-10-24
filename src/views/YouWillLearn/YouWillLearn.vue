<template>
    <section class="second-section">
        <h2 class="second-section-h2">O QUE VOCÊ APRENDERÁ EM AULA?</h2>

        <p class="second-section-p">Você vai aprender como usufruir ao máximo do seu corpo para se defender em quaisquer
            circunstâncias:</p>

        <ul>
            <li>-Socos extremamente poderosos, cotoveladas, chutes rápidos, joelhadas, torções, imobilizações (voltadas
                para a realidade da rua e autodefesa pura), quedas e projeções (voltadas para autodefesa);leitura de
                corpo e
                antecipação.</li>
            <li>-Energia, leitura de corpo e antecipação.</li>
        </ul>

        <span class="obs-span">Além também de um belíssimo arsenal de técnicas com armas
        brancas, ao qual se somam mais de 18 tipos de armas no sistema.</span>

    </section>
</template>

<script>
export default {
    name: 'YouWillLearn'
}
</script>

<style>
.second-section {
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

.second-section-texts {
    width: auto;
    height: auto;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.second-section h2 {
    color: gold;
    margin-bottom: 20px;
    text-align: center;
    font-size: 30px;
}

.second-section p {
    width: auto;
    height: auto;
    text-align: center;
    font-weight: 800;
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
    .second-section{
        width: auto;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 5px;
    }

    .obs-span{
        width: auto;
        height: auto;
        text-align: center;
    }
}
</style>