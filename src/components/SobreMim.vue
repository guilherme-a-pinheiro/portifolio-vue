<template>
  <div class="main">
      <div class="container">
        <div class="title">
            <h1>Sobre mim</h1>
        </div>
        <div class="text_img">
            <img src="../../public/imgs/image-perfil.jpeg" alt="">
            <p>aksjdklasjd</p>
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
        background: red;
        width: 60vw;
        height: 60vh;
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-direction: column;
    }

    .text_img {
        display: flex;
    }

    .text_img p {
        margin: 0px 70px;
    }

    .text_img img {
        width: 30vw;
        height: 55vh;
    }

    .title h1 {
        background: #070303;
        width: 60vw;
        text-align: center;
        color: #fff;
        padding: 6px;
        border-radius: 10px;
    }
</style>