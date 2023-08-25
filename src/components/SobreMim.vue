<template>
  <div class="main">
      <div class="container">
        <div class="title">
            <h2>Sobre mim</h2>
        </div>
        <div class="text_img">
            <img src="../../public/imgs/image-perfil.jpeg" alt="">
            <p>texto maneiro</p>
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
        width: 575px;
    }

    .text_img {
        display: flex;
        width: 60vw;
    }

    .text_img p {
        margin: 0px 70px;
    }

    .text_img img {
        width: 280px;
        height: 450px;
    }

    .title h2 {
        background: #070303;
        width: 575px;
        text-align: center;
        color: #fff;
        padding: 6px;
        border-radius: 10px;
    }

    .title {
        margin-bottom: 100px;
    }
</style>