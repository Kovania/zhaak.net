<script setup>
</script>

<template>
    <div class="bgr"></div>
    <div class="flex">
        <div>
            <h3>NICE TO MEET YOU.</h3>
            <h1>Hey, I'm Zhaak,</h1>
            <h1>a graphic designer.</h1>
            <p>
                Bonjour, je m'appelle Zhaak et je suis un graphiste basé en France. J'ai plus de 3 ans d'expérience dans la communauté des jeux et de l'esport. Au fil des ans, j'ai appris que le fait d'avoir des designs de médias sociaux saisissants est une très bonne première impression pour tous les publics. Que ce soit sur les flux, sur les vignettes vidéo, tous les types de graphiques sont cruciaux pour gagner en pertinence dans la communauté.
                <br><br>Ayant été dans la communauté pendant un certain temps, j'ai remarqué que l'industrie de l'esport et du jeu se développe énormément. Avec toute la croissance, il y a beaucoup de changements et être adaptatif est la clé.
            </p>
            <div class="author">
              <div class="gueule">
                <!--<img src="">-->
              </div>
              <div class="spacer"></div>
              <div class="text">
                <b>Zhaak</b><br>
                Graphic Designer
              </div>
            </div>
            <div class="contact">
              <div class="input">
                <div class="text">contact@zhaak.net</div>
                <div class="spacer"></div>
                <a href="mailto:contact@zhaak.net"><div class="send"></div></a>
              </div>
              <div class="spacer"></div>
              <div class="button">
                <a href="https://www.behance.net/Zhaak" target="blank"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABYAAAAQCAYAAAAS7Y8mAAAACXBIWXMAAA7DAAAOwwHHb6hkAAACDUlEQVR42o3UT0hUURTH8Sk1wT/R5JS4Cd2ZouDGxI0FloIQFEISCKWzkFBciQtXQn8EkUwRS9OhRYKrqBYhQZARBC0yAwuEcSFBlH8mDSkZfX7P8HtweRoofHwz79537r3nnDchz/PyEMGpgIjGTiIToYA0ZCBdMnQvNW7/7uMRxjCOx7ra94d4gMsHBC5GDarFPpdrkVTgw/x9xAV3R7iNL5jFW8xpg1l+4HU9/Asx9OIORvFZY7vafY4T+Br6NN8WuYsWd8cJPTyPksBxo86un+OEM3Yc59CIJtSi0M2xH/ir8pSuYoXRprF/uOcfE2eV+z+BlL1CvaXMTcUPTbZgnehXKnaU41IFtY55pmd+YgYvEdc9y3ulTVzTDQuwhQ1s4q/u23USBQp8Cysa60GuXNdz21ZEd8d2fYERVXda6UlqMWvBfDzVfAs+jJsqmhV8SWNxN8ffUKcChXXkS/ig8e+4iHf6vq3NrMq6TmwdtOYGttxUBLoiT2nwTxRVz/oL2cvVinbV5gaarUuCXXFeAY+pZ62VPmncanFVx/dr0RhoP1t4wOrg5vg3XuMJppTjeaeV3uMMqrCoe2/UQZbjQSyrBbsP80on1E4NOCLWGQvOnKTTWTEUhbT10f+wHHagLJB7e4muYAgTqoP9aHVZUE9vnt8FB7GxbBz19v+6+W+ndc9pFTpHJwrtASZZzo0JIZJFAAAAAElFTkSuQmCC"></a>
                <a href="https://twitter.com/ZhaakTv" target="blank"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAABmJLR0QA/wD/AP+gvaeTAAABJElEQVQ4jeXSMUtXcRTG8edaDUlqQYIghIsuTUGzNDWECPoqegG5uUkvQZzEQXFyaArcEtGpBnEIwknRQXTRSMjh4/IfLtd7f+rsM/045zzfc86PkzxeYeiOfIXP+IkDrOENBjDdZljFlwJwwW1d4BIzeNk07PaKljDYyA3ifwsQzrCJ503gSq3oEHMY6eXed8DgN160rfQWfxvF1/iDrQLwW53TV3vPJzlu9HmaZDzJZNffJjnpAu4mmSgYu7TTGsUzrBdWa9MVXne2wgf8eABwsTg7RnFyT9ip3hXcBR3DMo4LsGt8avP3tcTOk+wl6e/oeZVktqqq76WpXuErtt2+xbo2UbyEqgZ9kuRjkqkk75IMJ/mX5CjJryQbVVXtl2CPVDftsfGkHT7n7QAAAABJRU5ErkJggg=="></a>
                <a href="https://www.instagram.com/zhaaktv/" target="blank"><img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAABmJLR0QA/wD/AP+gvaeTAAABPUlEQVQ4jbWUPU5CQRRGzxAKEwtcgFoAbsAtaCOYECtXoLtxF2qCnbgItyBRKMBCa2NiDHgsGHB4PED8+ZLbfHPveffN3Bn4Y4U8U90BtoA1YD2z/Aq8Af0Qwv1CulpX235fbbW2CDZcATbWMBe6YmdP6oX6Pu50Zs+WAHoxxjqJdZeJV02B+3NA12olyauqLfVWPVGfk9y9FHg4B1ZQS+ppjFL0Wjn59RTYyCx+qBV1Q+0kfidCqznABkAhMouZM+qHEDrAMVBO/DJwHEJ4AB4zNcUUOE8uWZ/RGDjI+Nvx1JpAN/G7QNPRTdrM1AwmbQLDnI+dAUfALqNfF7gCXoDznPyvphaMTctkvhzN682c3KmxWTbY/RiLVJ3q19WuXlZ3Mxug1vz543CQs6cT6KrP1xTsNw9sLw74/+oTTq4N66QNJqgAAAAASUVORK5CYII="></a>
              </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
  .input {
    background: white;
    color: grey;
    border-radius: 100px;
    border: solid 1px grey;
    width: 330px;
    height: 50px;
    display: flex;
    align-items: center;
  }

  .input .text {
    margin-left: 20px;
    font-size: 18px;;
    color: rgb(216,216,216);
    font-style: italic;
  }

  .send {
    width: 42px;
    height: 42px;
    margin-right: 4px;
    border-radius: 100%;
    background: url('data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABIAAAAQCAYAAAAbBi9cAAAACXBIWXMAAA7DAAAOwwHHb6hkAAABM0lEQVR42p3TvyuFURzH8cfFLYNNBj8n3ZuSSZSBkcTIwGiX/AsKC6uiLEZlkUFk8WMVBoOUQSiJkkHy9f7me3M695xD99Srnuf8+PR8z3lOJiJZhaoxjE3cVBLQhWXc4UlDsPrfxU2Yxbn8thMc2nNvanEdJrGLTyfgCyvYsfdLne8vzmEQG3iV8qalTODA6Ztzg4qYx63E2xG6cer0faCxFLQl6aalLKIZZ97YdqmazHY91rSUEbTjKjA+6ga1Yj8wSUtoQyFS8j1q3CBVhRm8Wyn6n9TanjxEvnbJPSj/1DoxZM99eE6UXUwF9djX6ca+JEKOvXVlQQvYQwv6cR0Jmv4raNwmaklTqMeaF/Jm/cmgDmeBbvyA9esxP1r/ugSuVOiKXMjPZSx4Yw0YQz4U9A3Eo97U9wKHJwAAAABJRU5ErkJggg==') no-repeat center red;
  }

  .button {
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .button img {
    padding: 0 14px;
  }
  .contact {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 40px;
  }
  .author {
    display: flex;
    margin-top: 40px;
    width: 210px;
    justify-content: center;
    align-items: center;
  }

  .spacer {
    flex: 1;
  }

  .flex {
    display: flex;
    max-width: 900px;
    margin: 0 auto;
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

  p {
    margin-top: 30px;
  }

  .bgr {
    background: #151518;
    border-top-right-radius: 2.250rem;
    position: absolute;
    top: 10%;
    right: 25%;
    left: 0;
    bottom: 0;
  }

  .gueule {
    height: 57px;
    width: 57px;
    border-radius: 100%;
    background: url(../assets/sagueule.png);
    background-size: cover;
  }

  @media only screen and (max-width: 920px) {
    .flex {
      margin: 30px;
      display: initial;
    }
    h1 {
      font-size: 35px;
      line-height: 48px;
    }
    p {
      font-size: 14px;
    }
  }
</style>
