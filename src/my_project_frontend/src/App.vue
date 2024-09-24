<template>
  <div id="app" class="app-container">
    <Header />
    <AboutYou />
    <Projects />
    <Skills />
    <Contact />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import AboutYou from "./components/aboutYou.vue";
import Contact from "./components/Contact.vue";
import Projects from "./components/Projects.vue";
import Skills from "./components/Skills.vue";

export default {
  name: "App",
  components: {
    Header,
    AboutYou,
    Contact,
    Projects,
    Skills
  },
};
</script>