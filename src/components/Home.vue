<script setup>
</script>

<template>
  <div class="home">
    <div class="flex">
      <div class="text">
            <h1>Hey, I'm<br>
            <span class="red">Zhaak</span></h1>
            <p>
              Bonjour, je m'appelle Zhaak et je suis un graphiste français. J'ai plus de 3 ans d'expérience dans la conception graphique au sein de la communauté des jeux et de l'esport.
            </p>
      </div>
      <div class="pigeon">
        <img src="../assets/pigeon.png">
      </div>
    </div>
  </div>
</template>

<style scoped>
  .flex {
    display: flex;
    max-width: 900px;
    margin: 0 auto;
  }
  .flex div {
    flex: 1;
  }

  .pigeon {
    position: relative;
    height: 400px;
  }

  .pigeon img {
    position: absolute;
    top: 0px;
    width: 200px;
    right: 130px;
  }

  h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 57px;
    line-height: 76px;
    font-weight: 700;
  }

  h1 span {
    font-weight: 700;
  }

  .red {
    color: rgb(232,24,24);
  }

  p {
    margin-top: 20px;
  }

  @media only screen and (max-width: 900px) {
    .flex {
          margin: 30px;
    }
    .pigeon {
      display: none;
    }
  }

  @media only screen and (max-width: 690px) {

  }
</style>
