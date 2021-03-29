<template>
  <div class="advert">
    <div class="container">
      <div class="advert_grid">
        <div class="advert_grid-cell1 advert_image"></div>
        <div class="advert_grid-cell2 advert_image"></div>
        <div class="advert_grid-cell3 advert_image"></div>
        <div class="advert_grid-cell4 advert_image"></div>
        <div class="advert_grid-cell5 advert_image"></div>
        <div class="advert_grid-cell6 advert_image"></div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Advert",
};
</script>

<style scoped>

.advert_image {
  cursor: pointer;
  border-radius: 15px;
  background-size: 100% 100%;
  background-repeat: no-repeat;
  background-position: center;
}

.advert_image:hover {
  border: 2px solid red;
}

.advert {
  height: 650px;
  margin: 1rem 0 4rem 0;
}

.advert_grid {
  display: grid;
  height: 100%;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(3, 1fr);
  grid-gap: 20px;
}

.advert_grid > div {
  border-radius: 15px;
}

.advert_grid-cell1 {
  grid-column: 1/3;
  grid-row: 1/3;
  background-image: url("../images/advert1.png");
}

.advert_grid-cell2 {
  background-image: url("../images/advert2.png");
}

.advert_grid-cell3 {
  background-image: url("../images/advert3.png");
}

.advert_grid-cell4 {
  grid-column: 1/2;
  background-image: url("../images/advert4.png");
}

.advert_grid-cell5 {
  grid-column: 2/3;
  background-image: url("../images/advert5.png");
}

.advert_grid-cell6 {
  grid-column: 3/5;
  grid-row: 2/4;
  background-image: url("../images/advert6.png");
}
</style>