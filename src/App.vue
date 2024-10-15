<template>
  <Nav />
  <Header />
  <Section />
  <Main />
  <Footer />
</template>

<script>
import Nav from './components/Nav.vue';
import Header from './components/Header.vue';
import Section from './components/Section.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';


export default {
  components: {
    Nav,
    Header,
    Section,
    Main,
    Footer
  },
};
</script>

<style>
* {
    padding: 0;
    margin: 0%;
    text-decoration: none;
}

</style>
