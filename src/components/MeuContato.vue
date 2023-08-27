<template>
  <div class="main">
    <div class="container">
      <h2>Meu contato</h2>
      <div class="texto">
        <p>Caso tenha interesse no meu trabalho e/ou ache que posso te ajudar, pode entrar em contato comigo através do meu email :D</p>
        <div class="email">
          <p>
            guiapinheiro29@gmail.com
          </p>
        </div>
      </div>
      <div class="github">
        <p>
          Te convido também a dar uma olhada nos meus repositórios do <a href="https://github.com/guilherme-a-pinheiro" target="_blank">GitHub</a>!
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'MeuContato'
}
</script>

<style scoped>
  .main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
  }

  .container {
    height: 80vh;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
  }

  .container h2 {
      background: #070303;
        width: 575px;
        text-align: center;
        color: #fff;
        padding: 6px;
        border-radius: 10px;
  }

  .texto p {
    max-width: 575px;
    font-size: 25px;
  }

  .texto {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .email {
    margin: 20px 0px;
    font-size: 25px;
    text-decoration: underline;
  }

  .email p {
    background: rgb(128, 208, 128);
    padding: 10px;
    border-radius: 10px;
  }

  .github p {
    background: gray;
    padding: 20px;
    border-radius: 10px;
  }

  .github p a {
    text-decoration: none;
    background: inherit;
  }
  .github p a:hover {
    color: #fff
  }


</style>