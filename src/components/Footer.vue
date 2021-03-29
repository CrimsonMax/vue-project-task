<template>
  <div class="footer">
    <div class="container">
      <div class="footer_container">
        <div class="footer_message footer_margin">
          <p class="footer_message-text">Политика конфеденциальности</p>
          <p class="footer_message-copyright">© 2020 «Four group»</p>
        </div>
        <div class="footer_social footer_margin">
          <a target="_blank" rel="noopener noreferrer" href="https://vk.com">
            <i class="fab fa-vk cursor"></i>
          </a>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://www.instagram.com"
          >
            <i class="fab fa-instagram cursor"></i>
          </a>
          <a
            target="_blank"
            rel="noopener noreferrer"
            href="https://www.facebook.com/"
          >
            <i class="fab fa-facebook-square cursor"></i>
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.footer {
  margin-bottom: 1rem;
}

.footer_container {
  background-color: #fdfbf0;
  display: flex;
  justify-content: space-between;
  height: 100px;
  align-items: center;
  border-radius: 20px;
}

.footer_margin {
  margin: 0 2rem;
}

.footer_message {
  font-family: "OpenSans", sans-serif;
  display: flex;
  height: 50%;
  flex-direction: column;
  justify-content: space-around;
}

.footer_message-text {
  text-transform: uppercase;
}

.footer_social {
  font-size: xx-large;
}

.footer_social > i {
  cursor: pointer;
}

.footer_social > a {
  color: inherit;
}

a > .fa-instagram {
  margin: 0 1rem;
}
</style>