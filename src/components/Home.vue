<script setup>
</script>

<template>
  <div class="home">
    <div class="flex">
      <div class="text">
            <h1>Hey, I'm</h1>
            <h1>Zhaak</h1>
            <span>
              Bonjour, je m'appelle Zhaak et je suis un graphiste français. J'ai plus de 3 ans d'expérience dans la conception graphique au sein de la communauté des jeux et de l'esport.
            </span>
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
    right: 0px;
  }
</style>
