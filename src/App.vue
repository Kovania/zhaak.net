<script setup>
import Header from "./components/Header.vue"
import Home from "./components/Home.vue"
import About from "./components/About.vue"
import Portfolio from "./components/Portfolio.vue"
import Twitch from "./components/Twitch.vue"
import Contact from "./components/Contact.vue"
</script>

<template>
  <Header/>
  <main>
    <full-page ref="fullpage" :options="options" id="fullpage">
      <div class="section">
        <Home />
      </div>
      <div class="section">
        <About />
      </div>
      <div class="section">
        <Portfolio />
      </div>
      <div class="section">
        <Twitch />
      </div>
      <div class="section">
        <Contact />
      </div>
    </full-page>
  </main>
</template>

<style>
@import "./assets/base.css";

#app {
  margin: 0 auto;
  font-weight: normal;
  background: black;
}

.fp-watermark {
  display: none!important;
}

a,
.green {
  text-decoration: none;
  color: hsla(160, 100%, 37%, 1);
  transition: 0.4s;
}

.section {
  overflow: hidden;
}

@media (hover: hover) {
  a:hover {
    background-color: hsla(160, 100%, 37%, 0.2);
  }
}
</style>
