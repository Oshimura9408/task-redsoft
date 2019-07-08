<template>
  <div class="footer">
    <div class="footer-container">
      <div class="footer-logo"></div>
      <ul class="footer-menu-list">
        <li class="footer-menu-list__item">О сервисе</li>
        <li class="footer-menu-list__item">Функции</li>
        <li class="footer-menu-list__item">Возможности</li>
        <li class="footer-menu-list__item">Специалистам</li>
        <li class="footer-menu-list__item">88005004549</li>
      </ul>
    </div>
    <div class="dev">
      Разработка сайта
      <span>Redsoft</span>
    </div>
  </div>
</template>

<style lang="scss">
.footer {
  background: #39649d;
  color: #ffffff;
  padding-bottom: 30px;
  &-logo {
    background: url("../assets/logo-gray.png");
    background-repeat: no-repeat;
    width: 160px;
    height: 17px;
  }

  &-container {
    display: flex;
    justify-content: space-between;
    width: 1160px;
    margin: 0 auto;
    padding-top: 63px;
    padding-bottom: 56px;
    margin-bottom: 37px;
    border-bottom: 1px solid #335b91;
  }

  &-menu-list {
    display: flex;
    width: 760px;
    justify-content: space-between;

    &__item {
      margin-right: 67px;
      &:last-child {
        margin: 0;
      }
    }
  }
}

.dev {
  font-size: 14px;
  line-height: 21px;
  width: 172px;
  margin: 0 auto;
  span {
    color: #e70067;
  }
}
</style>

