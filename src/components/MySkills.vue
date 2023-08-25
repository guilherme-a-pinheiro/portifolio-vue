<template>
  <div class="main">
    <div class="container">
        <h2>Minhas habilidades</h2>
        <div class="buttons_container">
            <div class="buttons">
                <p>Big Query</p>
                <p>Python</p>
                <p>JavaScript</p>
            </div>
            <div class="buttons">
                <p>CSS</p>
                <p>SQL</p>
                <p>Excel</p>
            </div>
            <div class="buttons">
                <p>HTML</p>
                <p>VueJS</p>
                <p>Node</p>
            </div>
        </div>
    </div>
  </div>
</template>

<script>
export default {
    name: 'MySkills'
}
</script>

<style scoped>
    .main {
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    .container {
        height: 55vh;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }

    .container h2 {
        background: #070303;
        width: 800px;
        text-align: center;
        color: #fff;
        padding: 6px;
        border-radius: 10px;
    }

    .buttons {
        display: flex;
        height: 50px;
        width: 100%;
        justify-content: space-between;
    }

    .buttons p {
        background: #919191;
        font-weight: bold;
        height: 50px;
        width: 250px;
        border-radius: 10px;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .buttons_container {
        height: 300px;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
    }
</style>