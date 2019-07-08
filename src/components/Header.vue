<template>
  <div class="header">
    <div class="header-container">
      <a href class="logo"></a>

      <ul class="menu-list">
        <li class="menu-list__item">
          <a href="#about">О сервисе</a>
        </li>
        <li class="menu-list__item">
          <a href="#function">Функции</a>
        </li>
        <li class="menu-list__item">
          <a href="#personal">Возможности</a>
        </li>
        <li class="menu-list__item">
          <a href="#pattern">Паттерны</a>
        </li>
      </ul>
      <div class="btn btn-request btn-header">
        <span>Оставить заявку</span>
      </div>
    </div>

    <div class="header-text">
      <div
        class="header-text__title"
      >Расширяем возможности предоставления качественных медицинских услуг</div>
      <div
        class="header-text__desc"
      >«Дневник здоровья» – новый сервис для самоконтроля показателей состояния здоровья, разработанный для участников программы «Мое здоровье».</div>

      <div class="btn btn--red btn-more">
        <span>Узнать больше</span>
      </div>
    </div>
    <div class="slide-container">
      <div class="slide-control slide-control--active slide-control--prev"></div>
      <div class="slide-control slide-control-next"></div>
    </div>
  </div>
</template>

<style lang="scss">
.header {
  position: relative;
  background-image: url("../assets/slide-1.jpg");
  background-repeat: no-repeat;
  background-position: center;
  height: 751px;
  color: #ffffff;

  &-text {
    margin: 98px auto 0;
    width: 780px;
    text-align: center;
    letter-spacing: 0.1px;
    &__title {
      font-size: 37px;
      line-height: 54px;
      margin-bottom: 36px;
    }

    &__desc {
      width: 88%;
      font-size: 24px;
      line-height: 36px;
      margin: 0 auto 52px;
    }
  }
}

.logo {
  width: 200px;
  height: 40px;

  background: url("../assets/logo-white.png");
  background-repeat: no-repeat;
}

.btn {
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50px;
  font-size: 16px;
  height: 60px;
  width: 160px;
  color: #ffffff;
  cursor: pointer;
  transition: 0.3s;
  &:hover {
    transition: 0.3s;
    transform: scale(1.1);
  }

  &--red {
    background: #e70067;

    &:hover {
      background: #c9005a;
    }
  }

  &-request {
    width: 200px;

    font-weight: bold;
  }

  &-header {
    border: 1px solid #5489c3;
  }

  &-more {
    width: 180px;
    margin: 0 auto;
  }
}

.slide {
  &-container {
    position: absolute;
    bottom: 50px;
    left: calc(50% - 36px);
    width: 72px;
    height: 16px;
    border: 1px solid #5387c2;
    border-radius: 50px;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
  }

  &-control {
    width: 16px;
    border: 1px solid #5387c2;

    &--active {
      border-color: #fafbfd;
    }
  }
}

.header-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding-top: 14px;
  min-width: 1200px;
  max-width: 1200px;
  margin: 0 auto;
}

.menu-list {
  font-size: 16px;
  font-weight: bold;
  padding: 0;
  width: 490px;
  display: flex;
  justify-content: space-between;

  &__item {
    cursor: pointer;
    transition: 0.3s;
    position: relative;
    a {
      text-decoration: none;
      color: #ffffff;
    }
    &:hover {
      &::before {
        content: "\2022";
        color: #ffffff;
        font-weight: bold;
        display: block;
        position: absolute;
        bottom: -15px;
        left: 50%;
      }
    }
  }
}
</style>