<template>
  <div class="options">
    <div class="container">
      <div class="options_container">
        <div @click="homeRoute" class="options_logo">
          <div class="logo_base">
            <div class="logo_base-letter logo_letter-f">F</div>
            <div class="logo_base-letter logo_letter-ou">O</div>
            <div class="logo_base-letter logo_letter-ou">U</div>
            <div class="logo_base-letter logo_letter-r">R</div>
          </div>
          <div class="logo_text">GROUP</div>
        </div>
        <div class="options_button">
          <button>
            <i class="fas fa-bars"></i>
            <span class="button_text">Каталог</span>
          </button>
        </div>
        <div class="options_search">
          <input type="search" />
          <i class="fas fa-search"></i>
        </div>
        <div class="options_help">
          <div class="options_help-payment options_icons">
            <i class="far fa-money-bill-alt"></i>
            <p class="payment_text">Оплата</p>
          </div>
          <div class="options_help-delivery options_icons">
            <i class="fas fa-truck"></i>
            <p class="delivery_text">Доставка</p>
          </div>
          <div class="options_help-love options_icons">
            <i class="far fa-heart"></i>
            <p class="heart_text">Поддержка</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavBar",
  methods: {
    homeRoute() {
      this.$router.push("/");
    },
  },
};
</script>

<style scoped>
.options {
  height: 100px;
}

.options_container {
  display: flex;
  height: 100%;
  justify-content: space-between;
  align-items: center;
}

.options_logo {
  width: 100px;
  height: 100px;
  position: relative;
  bottom: 20px;
  user-select: none;
  cursor: pointer;
}

.logo_base {
  display: grid;
  width: 100px;
  height: 100px;
  grid-template-columns: 50px 50px;
  text-align: center;
  align-items: center;
  border: 2px solid black;
  grid-template-rows: 50px 50px;
  font-weight: 900;
  font-size: 20px;
}

.logo_letter-f {
  padding: 1rem 0;
  background: #c9d6a4;
  border: 1px solid;
}

.logo_letter-ou {
  background: #fff;
  padding: 1rem 0;
}

.logo_letter-r {
  background: #fbcf79;
  padding: 1rem 0;
  border: 1px solid;
}

.logo_text {
  font-size: 0.1rem;
  letter-spacing: 1rem;
  margin: 0.5rem;
}

.options_button > button {
  width: 180px;
  height: 50px;
  border: 2px solid rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  background: #ffffff;
  outline: none;
  cursor: pointer;
  display: flex;
  justify-content: center;
  align-items: center;
}

button > i {
  font-size: xx-large;
  color: #5b7004;
}

.button_text {
  font-family: "OpenSans", sans-serif;
  text-transform: uppercase;
  margin: 0 1rem;
  color: #494949;
}

.options_search > input {
  height: 50px;
  width: 612px;
  background: #ffffff;
  border: 2px solid rgba(0, 0, 0, 0.1);
  border-radius: 10px;
  outline: none;
  font-size: larger;
  padding-left: 10px;
}

.options_search > i {
  position: relative;
  right: 50px;
  font-size: larger;
}

.options_help {
  display: flex;
  align-items: center;
  text-align: center;
  height: 50px;
  color: #494949;
}

.options_icons {
  cursor: pointer;
}

.options_icons > i {
  background: #c9d6a4;
  border-radius: 50%;
}

.options_help-delivery {
  margin: 0 2rem;
}
</style>