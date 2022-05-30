<script setup>

</script>

<template>
    <div>
    <div class="flex">
            <h3>CONTACT ME</h3>
            <h1>Got a Project? Let's Talk!</h1>
            <div class="flexmail">
              <img width="40px" src="data:image/png;base64,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">
              <span>contact@zhaak.net</span>
            </div>
            <div class="flexfooter">
              <img width="60px" src="../assets/Logo_Zhaak2021_blanc.png">
              <div class="spacer"></div>
              <div class="menu">
                <a href="#about">About</a>
                <a href="#portfolio">Portfolio</a>
                <a href="#twitch">Twitch</a>
              </div>
        </div>
        </div>
        <div class="credit">
            © 2022 ZhaakDesigns.
        </div>
    </div>
</template>

<style scoped>
  h3 {
    color: red;
    font-weight: bold;
  }

  .flexx {
    display: flex;
    vertical-align: center;
    align-items: center;
  }

  .credit {
    max-width: 900px;
    margin: 0 auto;
    margin-top: 35px;
    font-size: 18px;
  }
  .flex {
    background: #151518;
    max-width: 900px;
    margin: 0 auto;
    border-radius: 22px;
    text-align: center;
    padding: 30px;
  }

  h1 {
    font-family: 'Poppins', sans-serif;
    font-size: 30px;
    line-height: 76px;
    font-weight: 500;
    margin-top: -5px;
  }

  .menu a {
    margin: 10px;
    color: white;
    font-weight: 500;
  }

  .flexmail {
    display:flex;
    max-width: 500px;
    align-items: center;
    justify-content: center;
    margin: 40px auto;
    margin-bottom: 60px;
  }

  .flexmail span {
    margin-left: 20px;
    font-size: 22px;
  }

  .spacer {
    flex: 1;
  }
  .flexfooter {
    display: flex;
    align-items: center;
    vertical-align: center;
  }
</style>
