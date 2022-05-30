<script setup>

</script>

<template>
    <div class="bgr"></div>
    <div>
      <div class="flex">
            <h3>PORTFOLIO</h3>
            <div style="display:flex;align-items: center;">
                <h1>All Creative Works</h1>
                <div class="spacer"></div>
                <div class="puce">NEW</div>
                <div class="come">Discover all projects on <a href="https://www.behance.net/Zhaak" target="_blank">Bēhance ></a></div>
            </div>

            <div class="fleximage">
              <div class="img" style="background: url(../assets/hyperion_mockup.png) no-repeat center/cover;"></div>
              <div class="spacer"></div>
              <div class="img" style="background: url(../assets/100_THIEVES.png) no-repeat center/cover;"></div>
              <div class="spacer"></div>
              <div class="img" style="background: url(../assets/fnatic_mockup.png) no-repeat center/cover;"></div>
            </div>
        </div>
    </div>
</template>

<style scoped>

  .fleximage {
    display: flex;
  }
  .flex {
    display: block;
    max-width: 940px;
    margin: 0 auto;
    align-items: center;
  }

  .spacer {
    flex: 1;
  }

  a {
    color: rgb(9,58,241);
    text-decoration: none;
    font-weight: bold;
  }
  .puce {
    background: rgb(9,58,241);
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
    top: 20%;
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

  .img {
    width: 290px;
    height: 290px;
    border-radius: 50px;
    margin-top: 80px;
  }
</style>
