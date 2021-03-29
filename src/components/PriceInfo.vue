<template>
  <div class="goods">
    <div class="container">
      <div class="goods_container">
        <div class="link_chain">
          <a href="/">Главная</a>
          <a href="/">/ Кухни</a>
          <a href="/">/ Кухни классика</a>
          <a href="/">/ Класика 1</a>
        </div>
        <div class="goods_info">
          <div class="goods_info-base">
            <div class="info_base-price">
              <div class="info_container">
                <h1 class="base_name">класика 1</h1>
                <h2 class="base_prise">80 000 &#8381;</h2>
                <small class="base_vendor">Артикул: </small
                ><small class="vendor_code">405268</small>
              </div>
              <div class="buy_container">
                <a href="/">купить в рассрочку</a>
                <p>от 3000&#8381; в месяц</p>
              </div>
              <div class="line"></div>
              <div class="support_container">
                <div class="base_support">
                  <i class="fas fa-truck"></i>
                  <p class="base_support-delivery">
                    Бесплатная доставка от 10 000 &#8381;
                  </p>
                </div>
                <div class="base_support">
                  <i class="fas fa-map-marker-alt"></i>
                  <a href="/" class="base_support-availability"
                    >Проверить наличие</a
                  >
                </div>
                <div class="base_support">
                  <i class="fas fa-retweet"></i>
                  <p class="base_support-size">Габариты: 160x200x80 см</p>
                </div>
                <div class="base_support">
                  <i class="fas fa-weight-hanging"></i>
                  <p class="base_support-weight">Вес: 45 кг</p>
                </div>
              </div>
            </div>
            <div class="info_base_photo">
              <div class="base_photo-main">
                <img src="../images/classic1.jpg" alt="" />
              </div>
              <div class="base_photo-sub">
                <div class="base_photo-sub1">
                  <img src="../images/classic2.jpg" alt="" />
                </div>
                <div class="base_photo-sub2">
                  <img src="../images/classic3.jpg" alt="" />
                </div>
                <div class="base_photo-sub3">
                  <img src="../images/classic4.jpg" alt="" />
                </div>
              </div>
            </div>
          </div>
          <div class="goods_info-text">
            <div class="info_text text-1">
              <p>
                Эта кровать классического дизайна будет прекрасно смотреться с
                вашей мебелью и текстилем для спальни. Легко создать гармоничный
                интерьер можно, дополнив другими товарами.
                <br />
                Два больших ящика превращают пустующее пространство под кроватью
                в практичное решение для хранения одеял, подушек и постельного
                белья.
                <br />
                В комбинацию входят узкий и широкий ящик, что позволяет
                организовать удобно хранение, разделив одеяла и постельное
                белье.
              </p>
            </div>
            <div class="info_text text-2">
              <p>
                Эта кровать классического дизайна будет прекрасно смотреться с
                вашей мебелью и текстилем дляспальни. Легко создать гармоничный
                интерьер можно, дополнив другими товарами.
                <br />
                Два больших ящика превращают пустующее пространство под кроватью
                в практичное решение для хранения одеял, подушек и постельного
                белья.
                <br />
                В комбинацию входят узкий и широкий ящик, что позволяет
                организовать удобно хранение, разделив одеяла и постельное
                белье.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PriceInfo",
};
</script>

<style scoped>
img {
  width: 100%;
  height: 100%;
  border-radius: 15px;
}

.goods {
  margin: 1rem 0;
}

.goods_info-base {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.info_base-price {
  width: 710px;
  height: 525px;
  background: #fdfbf0;
  border-radius: 15px;
  font-family: "OpenSans", sans-serif;
  margin: 5px 10px 10px 0;
}

.info_container > h1 {
  text-transform: uppercase;
  font-size: 45px;
}

.info_container > h2 {
  font-weight: 700;
  font-size: 45px;
  text-transform: uppercase;
}

.buy_container > a {
  text-transform: uppercase;
  color: #708208;
}

.buy_container > p {
  text-transform: uppercase;
}

.line {
  border: 1px solid #94af4a;
  height: 0;
  margin: 2.5rem 1rem;
}

.info_container {
  margin: 1rem;
}

.support_container,
.buy_container {
  margin: 2rem 1rem;
}

.base_support {
  align-items: center;
  display: flex;
  margin: 2.8rem 0;
  color: #494949;
}

.base_support > i {
  width: 20px;
  margin-right: 1rem;
  background: #c9d6a4;
  border-radius: 50%;
}

.base_support > a {
  color: #708208;
}

.info_base_photo {
  width: 710px;
  height: 525px;
  margin: 5px 0px 10px 10px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.base_photo-main {
  height: 355px;
  margin-bottom: 10px;
}

.base_photo-sub {
  height: 150px;
  display: flex;
  align-items: center;
  margin-top: 10px;
}

.base_photo-sub > div {
  height: 100%;
  width: 100%;
  cursor: pointer;
}

.base_photo-sub2 {
  margin: 0 20px;
}

.goods_info-text {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.info_text {
  width: 710px;
  height: 225px;
  background: #fdfbf0;
  border-radius: 15px;
  line-height: 27px;
  padding: 10px 25px;
  font-family: "OpenSans", sans-serif;
}

.info_text.text-1 {
  margin: 10px 10px 45px 0;
}

.info_text.text-2 {
  margin: 10px 0px 45px 10px;
}
</style>