<template>
  <Header />
  <NavBar />
  <NavSelect />
  <router-view />
  <Footer />
</template>

<script>
import Header from "./components/Header";
import NavBar from "./components/NavBar";
import NavSelect from "./components/NavSelect";
import Footer from "./components/Footer";

export default {
  components: { Header, NavBar, NavSelect, Footer },
  methods: {
    handleClick() {
      console.log("click");
      this.$router.push("/about");
    },
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Open+Sans&family=Roboto:wght@500&display=swap");

*,
*::after,
*::before {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-weight: inherit;
  font-size: inherit;
}

a,
a:visited {
  text-decoration: none;
}

a:focus,
a:active {
  outline: none;
}

ul li {
  list-style: none;
}

.container {
  width: 1200px;
  margin: 0 auto;
  height: 100%;
}
</style>
