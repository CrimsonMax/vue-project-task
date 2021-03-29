<template>
  <div class="header">
    <div class="container">
      <div class="header_contacts">
        <div class="contacts_mail contacts_flex">
          <i class="far fa-envelope"></i>
          <p class="contacts_mail-text contacts_margin">mebel@mail.ru</p>
        </div>
        <div class="contacts_adress contacts_flex">
          <i class="fas fa-map-marker-alt"></i>
          <p class="contacts_adress-text contacts_margin">
            Санкт-Петербург, ул. Ленина, д. 1
          </p>
        </div>
        <div class="contacts_phone contacts_flex">
          <i class="fas fa-phone-alt"></i>
          <p class="contacts_phone-text contacts_margin">+ 7 911 985 98 22</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header {
  height: 50px;
  background-color: #c9d6a4;
  width: 100%;
}

.header_contacts {
  display: flex;
  justify-content: flex-end;
  align-items: center;
  height: 100%;
}

.contacts_flex > i {
  cursor: pointer;
}

.contacts_flex {
  display: flex;
  align-items: center;
}

.contacts_margin {
  margin-left: 0.5rem;
}

.contacts_adress {
  margin: 0 2rem;
}

.contacts_adress,
.contacts_mail,
.contacts_phone {
  font-family: "OpenSans", sans-serif;
}
</style>