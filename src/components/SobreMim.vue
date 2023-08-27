<template>
  <div class="main">
      <div class="container">
        <div class="title">
            <h2>Sobre mim</h2>
        </div>
        <div class="text_img">
            <img src="../../public/imgs/image-perfil.jpeg" alt="">
            <p>Como um entusiasta desenvolvedor web, busco oportunidades desafiadoras para participar em projetos de impacto significativo. Minha jornada teve início em 2021, e desde então, tenho me dedicado ao aprendizado contínuo das inovações tecnológicas, principalmente focado no ecossistema Javascript e seus frameworks. Minha abordagem resiliente e apaixonada para superar obstáculos reflete minha busca constante por crescimento.<br>
            Além de minha paixão pelo desenvolvimento, estou cursando Análise e Desenvolvimento de Sistemas desde 2022, enriquecendo minha compreensão teórica com aplicações práticas. Meu comprometimento se resume em três palavras: perseverança, dedicação e esforço.
            </p>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'SobreMim'
}
</script>

<style scoped>
    .main {
        border-bottom: 5px solid #000;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .container {
        max-width: 600px;
    }

    .text_img {
        display: flex;
        width: 60vw;
    }

    .text_img p {
        margin: 0px 0px 0px 40px;
        max-width: 300px;
    }

    .text_img img {
        width: 280px;
        height: 450px;
    }

    .title h2 {
        background: #070303;
        width: 600px;
        text-align: center;
        color: #fff;
        padding: 6px;
        border-radius: 10px;
    }

    .title {
        margin-bottom: 100px;
    }
</style>