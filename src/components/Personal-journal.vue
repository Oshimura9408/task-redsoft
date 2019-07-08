<template>
  <div class="personal-journal" id="personal">
    <div class="personal-journal-title">Ведите персональный дневник мониторинга здоровья</div>
    <div class="personal-journal-container">
      <ul class="personal-journal-list">
        <li class="personal-journal-list__item">
          <div class="personal-journal-list__item__circle">1</div>
          <div class="personal-journal-list__item-title">Хранение данных</div>
          <div
            class="personal-journal-list__item-description"
          >Контролируйте и следите за динамикой изменения показателей вашего здоровья. Вносите результаты измерений медицинских показателей вручную или с помощью интегрированных приборов, храните историю измерений и отслеживайте динамику состояния здоровья</div>
        </li>
        <li class="personal-journal-list__item">
          <div class="personal-journal-list__item__circle">2</div>
          <div class="personal-journal-list__item-title">Сообшение информации врачу</div>
          <div class="personal-journal-list__item-description">
            Позвольте специалисту дистанционно следить за вашим здоровьем.
            Будьте на связи со специалистом - отправляйте информацию о своем самочувствии, обменивайтесь сообщениями и получайте рекомендации по вашему здоровью и лечению.
          </div>
        </li>
        <li class="personal-journal-list__item">
          <div class="personal-journal-list__item__circle">3</div>
          <div class="personal-journal-list__item-title">Напоминание о важном</div>
          <div class="personal-journal-list__item-description">
            Получайте рекомендации, созданные специально для вас.
            Система, персонально настроенная под ваши требования, автоматически напомнит о необходимости выполнить рекомендации медицинского специалиста: принять препарат или выполнить измерения.
          </div>
        </li>
      </ul>
      <div class="img-phones"></div>
    </div>
  </div>
</template>

<style lang="scss">
.personal-journal {
  padding-bottom: 190px;
  &-title {
    color: #31496b;
    font-size: 36px;
    line-height: 54px;
    width: 980px;
    margin: 0 auto;
    margin-top: 151px;
  }
  &-container {
    width: 1310px;
    display: flex;
    margin: 0 auto;
  }
  &-list {
    margin-top: 89px;
    margin-left: 56px;
    &__item {
      color: #60759d;
      width: 567px;
      position: relative;
      margin-bottom: 71px;
      margin-left: 75px;

      &__circle {
        position: absolute;
        z-index: -1;
        top: -36px;
        left: -111px;
        width: 123px;
        height: 123px;
        display: flex;
        justify-content: center;
        align-items: center;
        border: 2px solid rgba($color: #23b3e2, $alpha: 0.25);
        border-radius: 100px;
        font-size: 60px;
        color: rgba($color: #23b3e2, $alpha: 0.4);
        &::before {
          content: "";
          display: block;
          position: absolute;
          width: 20px;
          height: 130px;
          left: 102px;
          background: #ffffff;
        }
      }

      &-title {
        font-size: 24px;
        line-height: 36px;
        font-weight: 600;
        margin-bottom: 7px;
      }

      &-description {
        font-size: 16px;
        line-height: 24px;
        font-weight: 600;
      }
    }
  }
}

.img-phones {
  background: url("../assets/mokap-phones.jpg");
  background-repeat: no-repeat;
  width: 611px;
  height: 608px;
  margin-top: 90px;
  margin-left: 31px;
}
</style>

