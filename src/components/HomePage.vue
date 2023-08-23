<template>
    <div class="main">
        <div class="container">
            <h1>Seja bem vindo,</h1>
            <h2>Meu nome é</h2>
            <h2 class="color">Guilherme Pinheiro - Futuro Desenvolvedor de Software</h2>
            <h2>E quero te contar um pouco mais sobre mim.</h2>
        </div>
    </div>
</template>

<script>

export default {
    name: 'HomePage'
}
</script>

<style scoped>

    .container {
        width: 45vw;
        height: 40vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    .main {
        border-bottom: 5px solid #000;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    h1 {
        font-size: 50px;
        font-family: 'Lobster', cursive;
    }

    h1, h2 {
        margin: 10px;
        padding: 10px;
    }

    .color {
        background-color: rgb(121, 148, 121);
        border-radius: 4px;
    }
</style>