<script setup>

</script>

<template>
    <div class="bgr"></div>
    <div class="flex">
        <div>
            <h3>TWITCH</h3>
            <div class="flex">
              <h1>My Streaming Twitch</h1>
              <div class="spacer"></div>
              <div class="puce">LIVE</div>
              <div class="come">Come see my live on <a href="https://www.twitch.tv/zhaakfx" target="_blank">Twitch ></a></div>
            </div>
            <img src="../assets/twitch.png">
        </div>
    </div>
</template>

<style scoped>
  .flex {
    display: flex;
    max-width: 940px;
    margin: 0 auto;
    vertical-align: center;
    align-items: center;
  }

  .spacer {
    width: 35px;
  }

  a {
    color: rgb(100,70,164);
    text-decoration: none;
    font-weight: bold;
  }
  .puce {
    background: rgb(100,70,164);
    border-radius: 10px;
    width: 40px;
    font-size: 11px;
    height: 16px;
    text-align: center;
  }
  .come {
    margin-left: 10px;
  }

  .bgr {
    background: #151518;
    border-top-left-radius: 2.25rem;
    border-bottom-left-radius: 2.25rem;
    position: absolute;
    left: 38%;
    right: 0;
    bottom: 0;
    top: 15%;
    height: 330px;
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

  img {
    width: 700px;
    height: auto;
    border-radius: 50px;
    margin-top: 60px;
  }
</style>
