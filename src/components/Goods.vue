<template>
  <div class="grid_goods">
    <div class="container">
      <div class="grid_goods-container">
        <div class="grid_goods-header">
          <p>комнаты</p>
        </div>
        <div class="grid_goods-net">
          <div class="grid_cell-1">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a1"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid1.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-2">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a2"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid2.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло винтажное</p>
                <p>7 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-3">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a3"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid3.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван круглый</p>
                <p>16 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-4">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a4"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid4.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло терракот</p>
                <p>13 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-5">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a5"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid5.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван кантри</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-6">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a6"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid6.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло кожаное</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-7">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a7"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid7.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван загородный</p>
                <p>33 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-8">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a8"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid8.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло желтое</p>
                <p>13 000 &#8381;</p>
              </div>
            </div>
          </div>
        </div>

        <div class="grid_goods-net">
          <div class="grid_cell-1">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a9"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid9.jpg') + ')',
              }"
            >
              <div class="grid_good-name 9">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван для гостей</p>
                <p>12 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-2">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a10"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid10.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло мягкое</p>
                <p>13 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-3">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a11"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid11.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван зеленый</p>
                <p>33 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-4">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a12"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid12.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло черное</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-5">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a13"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid13.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван для гостей</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-6">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a14"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid14.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло-качалка</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-7">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a15"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid15.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>диван синий</p>
                <p>12 000 &#8381;</p>
              </div>
            </div>
          </div>
          <div class="grid_cell-8">
            <div
              @click="aboutRoute"
              class="grid_good"
              id="a16"
              v-bind:style="{
                'background-image':
                  'url(' + require('../images/grid16.jpg') + ')',
              }"
            >
              <div class="grid_good-name">
                <h2>Гостиные</h2>
                <i class="fas fa-heart"></i>
              </div>
              <div class="grid_good-price">
                <p>кресло строгое</p>
                <p>3 000 &#8381;</p>
              </div>
            </div>
          </div>
        </div>

        <div class="grid_goods-more">
          <button>Еще</button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Goods",
  methods: {
    aboutRoute() {
      this.$router.push("/about");
    },
  },
};
</script>

<style scoped>
.grid_goods {
  margin: 1rem 0 4rem 0;
}

.grid_goods-header {
  text-transform: uppercase;
  font-size: 35px;
}

.grid_goods-net {
  height: 850px;
  margin: 1rem 0 2rem 0;
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  grid-template-rows: repeat(5, 1fr);
  grid-gap: 20px;
}

.grid_goods-net > div {
  border-radius: 15px;
}

.grid_cell-1,
.grid_cell-3 {
  grid-row: 1/4;
  height: 100%;
}

.grid_cell-2,
.grid_cell-4 {
  grid-row: 1/3;
  height: 100%;
}

.grid_cell-5,
.grid_cell-7 {
  grid-row: 4/6;
  height: 100%;
}

.grid_cell-6,
.grid_cell-8 {
  grid-row: 3/6;
  height: 100%;
}

.grid_good {
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  height: 100%;
  padding: 1rem;
  font-family: "OpenSans", sans-serif;
  color: #050505;
  cursor: pointer;
  border-radius: 15px;
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}

.grid_good:hover {
  border: 2px solid black;
}

.grid_good-name {
  align-items: center;
  display: flex;
  justify-content: space-between;
}

.grid_good-name > i {
  color: #fff;
  cursor: pointer;
}

.grid_good-name > i:hover {
  color: red;
}

.grid_good-price {
  text-transform: uppercase;
}

.grid_goods-more {
  display: flex;
  justify-content: center;
  align-items: center;
}

.grid_goods-more > button {
  color: white;
  width: 80px;
  height: 35px;
  background: rgba(148, 175, 74, 0.7);
  border-radius: 15px;
  outline: none;
  cursor: pointer;
}

#a9 > .grid_good-name > i {
  color: red;
}

#a14 > .grid_good-name > i {
  color: red;
}

#a16 > .grid_good-name > i {
  color: red;
}
</style>