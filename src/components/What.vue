<template>
  <div  class="what" id="about">
    <div class="what-container">
      <div class="img-mobile"></div>
      <ul class="property-list">
        <div class="property-list__title">Что такое «Дневник здоровья»?</div>
        <div class="property-list__text">Дневник пациента — это удобный онлайн-сервис:</div>
        <li class="property-list__item">
          Вносите результаты измерений вручную или с помощью
          интегрированных приборов
        </li>
        <li class="property-list__item">
          Ведите персональную медицинскую карту с историей
          ваших измерений
        </li>
        <li class="property-list__item">
          Делитесь результатами измерений со специалистами
          для повышения эффективности лечения
        </li>
        <li class="property-list__item">Получайте рекомендации, созданные специально для вас</li>
        <div class="btn btn--red btn-request">Оставить заявку</div>
      </ul>
    </div>
    <div class="pulse"></div>
  </div>
</template>

<style lang="scss">
.what {
  position: relative;
  padding-top: 149px;
  width: 1200px;
  margin: 0 auto;
  padding-bottom: 86px;
  &-container {
    color: #60759d;
    display: flex;
    width: 1200px;
    margin: 0 auto;
  }
}
.img-mobile {
  background: url("../assets/phone.jpg");
  background-repeat: no-repeat;
  width: 335px;
  height: 652px;
}

.property-list {
  font-size: 16px;
  font-weight: 600;
  padding-top: 86px;
  padding-left: 42px;
  &__title {
    margin-bottom: 18px;
    font-size: 36px;
    line-height: 54px;
  }

  &__text {
    margin-bottom: 21px;
  }

  &__item {
    position: relative;
    width: 465px;
    margin-bottom: 24px;
    line-height: 21px;
    padding-left: 15px;
    &:nth-last-child(2) {
      margin-bottom: 32px;
      width: 470px;
    }
    &::before {
      content: "\2022";
      color: #16afe0;
      font-weight: bold;
      position: absolute;
      left: 0;
    }
  }
}

.pulse {
  display: block;
  position: absolute;
  width: 495px;
  height: 318px;
  background: url("../assets/pulse.jpg");
  background-repeat: no-repeat;
  bottom: -38px;
  right: -128px;
  /* overflow: hidden; */
  z-index: 13;
  bottom: -14px;
  right: -128px;
  /* overflow: hidden; */
  z-index: 13;
  transform: rotate(3deg);
}
</style>

