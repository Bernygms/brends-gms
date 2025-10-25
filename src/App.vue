<template>
  <div>
    <Home />
    <Music />
    <Videos />
    <About />
    <Contact />
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Music from './components/Music.vue'
import Videos from './components/Videos.vue'
import About from './components/About.vue'
import Contact from './components/Contact.vue'

export default {
  components: { Home, Music, Videos, About, Contact }
}
</script>

