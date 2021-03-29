<template>
  <Advert />
  <Goods />
</template>

<script>
// @ is an alias to /src
import Advert from "../components/Advert";
import Goods from "../components/Goods";

export default {
  name: "Home",
  components: {
    Advert,
    Goods,
  },
};
</script>
