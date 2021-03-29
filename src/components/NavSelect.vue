<template>
  <div class="navbar">
    <div class="container">
      <div class="navbar_menu">
        <ul class="navbar_menu-list">
          <li>
            <p class="navbar_menu-list_item">Акции и скидки</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Кухни</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Детские</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Спальни</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Корпусная мебель</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Офисная мебель</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Торговое оборудование</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Услуги</p>
          </li>
          <li>
            <p class="navbar_menu-list_item">Статьи</p>
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "NavSelect",
};
</script>

<style scoped>
.navbar {
  height: 40px;
}

.navbar_menu {
  height: 100%;
}

.navbar_menu-list {
  display: flex;
  justify-content: space-between;
  align-items: center;
  height: 100%;
}

.navbar_menu-list_item {
  text-transform: uppercase;
  font-family: "OpenSans", sans-serif;
  cursor: pointer;
}

.navbar_menu-list_item:hover {
  font-weight: bolder;
}
</style>