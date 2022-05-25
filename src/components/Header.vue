<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
});
</script>

<template>
  <div class="bgr">
    <div class="header">
      <div class="logo">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACEAAAAbCAYAAADyBeakAAAACXBIWXMAAA7DAAAOwwHHb6hkAAACsElEQVR42qWXX2iOURzHX0yyGUUyrjAkr8kNK2O9tWTalN3gQmFacyXZHVeSvzdo3LE/akJyIRcoMcsWSoqWP6XcmNpKZmjI1/c85zfveR/nPM95nvdXn953zznnd77v7/n9zvktg0wm4w0wnTSRdvKMjCNvg6ST7CJzk/j13XwOOUl+odB+k2HyHf9bF2kgU4oXAewkPw3nF8hmsoBMCgndQI4a888XHwngmLH5WTLfM3IzyHqSJRclKh3y/TZpM39AlJMHsvlo4DBJ7mgfZbLWZmv9IgGcIwcTb67XLiV/LJv3+b0OoJ4cJy1kDzlATsSgkvY6WUwqyGuLABXZhaQqWgSwA+ntFqkhI5axR+L/TfCXUwSwtQgBZ8g08sEy9sLY4608qysUAUyVkKY1VZIqkT9Zxp4G/vMicvK8NyyiErpseqASETgEXVJxdJPdst72Cp44kvaHjJeZIiYbExqhDpxkJ+k3i4CBgggUrrkpc6ptObFcBt97CsjBbo9j1h2RedtsItbI4FUPARsdAvo91rbJ3GabiNUyeCPGySaHgF54XFZQ94m2vTYRFTI4GOGg0SHgSoI8Uq3A5aCiHIfVRH9QmuAVqEpRfYY6qOo9yAVJqT+bSVV4o2viuCn0vMEh4BSZFyRzOhsj2bCIGhkcMJ5tiRBQTj6mFPCKzHRdYGPBFP292uHgEvIlncZewnjlNhGt0DdoncOBuuLVMd1PPpN3Magb9T65S57LZ0l8PwGscgjokvESMjtBRSyDTsQVvv3EPoeA7pQNzn7Dx8p4EfocUB3RuIT6C3SLdjrF5kuge4wJc7aI4YWLoC+lUugesTwIO1ArCXuHrIvZPCt5Y1ZBZdQa31/V+q9qtH0lD6Gv83aplntkyJij/ic57OM/aYi3h0Jssz4RPcvX718llZdjzx+aKwAAAABJRU5ErkJggg==">
      </div>
      <div class="nav">
        <ul>
          <li>One</li>
          <li>Two</li>
          <li>Three</li>
          <li>Viva</li>
          <li>L'Algérie</li>
        </ul>
      </div>
      <div class="spacer"></div>
      <div class="button">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABYAAAAQCAYAAAAS7Y8mAAAACXBIWXMAAA7DAAAOwwHHb6hkAAACDUlEQVR42o3UT0hUURTH8Sk1wT/R5JS4Cd2ZouDGxI0FloIQFEISCKWzkFBciQtXQn8EkUwRS9OhRYKrqBYhQZARBC0yAwuEcSFBlH8mDSkZfX7P8HtweRoofHwz79537r3nnDchz/PyEMGpgIjGTiIToYA0ZCBdMnQvNW7/7uMRxjCOx7ra94d4gMsHBC5GDarFPpdrkVTgw/x9xAV3R7iNL5jFW8xpg1l+4HU9/Asx9OIORvFZY7vafY4T+Br6NN8WuYsWd8cJPTyPksBxo86un+OEM3Yc59CIJtSi0M2xH/ir8pSuYoXRprF/uOcfE2eV+z+BlL1CvaXMTcUPTbZgnehXKnaU41IFtY55pmd+YgYvEdc9y3ulTVzTDQuwhQ1s4q/u23USBQp8Cysa60GuXNdz21ZEd8d2fYERVXda6UlqMWvBfDzVfAs+jJsqmhV8SWNxN8ffUKcChXXkS/ig8e+4iHf6vq3NrMq6TmwdtOYGttxUBLoiT2nwTxRVz/oL2cvVinbV5gaarUuCXXFeAY+pZ62VPmncanFVx/dr0RhoP1t4wOrg5vg3XuMJppTjeaeV3uMMqrCoe2/UQZbjQSyrBbsP80on1E4NOCLWGQvOnKTTWTEUhbT10f+wHHagLJB7e4muYAgTqoP9aHVZUE9vnt8FB7GxbBz19v+6+W+ndc9pFTpHJwrtASZZzo0JIZJFAAAAAElFTkSuQmCC">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAABmJLR0QA/wD/AP+gvaeTAAABJElEQVQ4jeXSMUtXcRTG8edaDUlqQYIghIsuTUGzNDWECPoqegG5uUkvQZzEQXFyaArcEtGpBnEIwknRQXTRSMjh4/IfLtd7f+rsM/045zzfc86PkzxeYeiOfIXP+IkDrOENBjDdZljFlwJwwW1d4BIzeNk07PaKljDYyA3ifwsQzrCJ503gSq3oEHMY6eXed8DgN160rfQWfxvF1/iDrQLwW53TV3vPJzlu9HmaZDzJZNffJjnpAu4mmSgYu7TTGsUzrBdWa9MVXne2wgf8eABwsTg7RnFyT9ip3hXcBR3DMo4LsGt8avP3tcTOk+wl6e/oeZVktqqq76WpXuErtt2+xbo2UbyEqgZ9kuRjkqkk75IMJ/mX5CjJryQbVVXtl2CPVDftsfGkHT7n7QAAAABJRU5ErkJggg==">
        <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAACNiR0NAAAABmJLR0QA/wD/AP+gvaeTAAABPUlEQVQ4jbWUPU5CQRRGzxAKEwtcgFoAbsAtaCOYECtXoLtxF2qCnbgItyBRKMBCa2NiDHgsGHB4PED8+ZLbfHPveffN3Bn4Y4U8U90BtoA1YD2z/Aq8Af0Qwv1CulpX235fbbW2CDZcATbWMBe6YmdP6oX6Pu50Zs+WAHoxxjqJdZeJV02B+3NA12olyauqLfVWPVGfk9y9FHg4B1ZQS+ppjFL0Wjn59RTYyCx+qBV1Q+0kfidCqznABkAhMouZM+qHEDrAMVBO/DJwHEJ4AB4zNcUUOE8uWZ/RGDjI+Nvx1JpAN/G7QNPRTdrM1AwmbQLDnI+dAUfALqNfF7gCXoDznPyvphaMTctkvhzN682c3KmxWTbY/RiLVJ3q19WuXlZ3Mxug1vz543CQs6cT6KrP1xTsNw9sLw74/+oTTq4N66QNJqgAAAAASUVORK5CYII=">
      </div>
    </div>
  </div>
</template>

<style scoped>
.header {
  max-width: 910px;
  margin: 0 auto;
  height: 61px;
  display: flex;
  justify-content: center;
  align-items: center;
  background: black;
  z-index: 999;
}

ul {
  list-style-type: none;
  display: inline-flex;
  margin: 0;
}

ul li {
  padding: 0 14px;
  font-weight: bold;
}

.button {
  display: flex;
  justify-content: center;
  align-items: center;
}

.button img {
  padding: 0 14px;
}

h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.spacer {
  flex: 1;
}

.bgr {
  background: black;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  height: 64px;
  z-index: 9999;
}
</style>
