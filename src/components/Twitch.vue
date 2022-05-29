<script setup>

</script>

<template>
    <div class="bgr"></div>
    <div class="flex">
        <div>
            <h3>TWITCH</h3>
            <h1>My Streaming Twitch</h1>
            
        </div>
    </div>
</template>

<style scoped>
  .flex {
    display: flex;
    max-width: 900px;
    margin: 0 auto;
  }

  .bgr {
    background: #151518;
    border-top-left-radius: 2.25rem;
    border-bottom-left-radius: 2.25rem;
    position: absolute;
    left: 25%;
    right: 0;
    bottom: 0;
    top: 15%;
    height: 260px;
  }

  h3 {
    color: rgb(235,25,25);
    font-weight: 500;
    letter-spacing: 1px;
  }

  h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 56px;
    line-height: 76px;
    font-weight: 700;
  }
</style>
