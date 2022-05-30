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
      <div class="section" data-anchor="home">
        <Home />
      </div>
      <div class="section" data-anchor="about">
        <About />
      </div>
      <div class="section" data-anchor="portfolio">
        <Portfolio />
      </div>
      <div class="section" data-anchor="twitch">
        <Twitch />
      </div>
      <div class="section" data-anchor="contact">
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
  color: white;
  transition: 0.4s;
}

.section {
  overflow: hidden;
}

</style>
