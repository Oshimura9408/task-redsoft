<template>
  <div id="app">
    <Header />
    <What />
    <Func />
    <PersonalJ />
    <Specialists />
    <Subscribe />
    <Footer />
  </div>
</template>

<script>
import Home from "./components/Home";
import Header from "./components/Header";
import What from "./components/What";
import Func from "./components/Func";
import PersonalJ from "./components/Personal-journal";
import Specialists from "./components/Specialists";
import Subscribe from "./components/Subscribe";
import Footer from "./components/Footer";

export default {
  name: "app",
  components: {
    Home,
    Header,
    What,
    Func,
    PersonalJ,
    Specialists,
    Subscribe,
    Footer
  }
};
</script>

<style>
@font-face {
  font-family: "Cera Round Pro";
  src: local("CeraRoundPro-Regular"),
    url("./fonts/CeraRoundPro-Regular.woff2") format("woff2"),
    url("./fonts/CeraRoundPro-Regular.woff") format("woff");
  font-weight: normal;
  font-style: normal;
}

html {
  scroll-behavior: smooth;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  list-style: none;
}

#app {
  font-family: "Cera Round Pro";
}
</style>
