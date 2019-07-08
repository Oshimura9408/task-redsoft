<template>
  <div class="specialists" id="pattern">
    <div class="img-scheme"></div>

    <ul class="specialists-list property-list__text">
      <div class="specialists-title property-list__title">Специалистам</div>
      <li
        class="specialists-list__item property-list__item"
      >Дистанционный контроль состояния здоровья ваших пациентов</li>
      <li class="specialists-list__item property-list__item">
        Наблюдение за динамикой изменения основных
        медицинских показателей
      </li>
      <li class="specialists-list__item property-list__item">
        Наличие алгоритмов автоматического анализа
        поступающей информации
      </li>
      <li class="specialists-list__item property-list__item">
        Индивидуальная система уведомлений об изменении
        состояния каждого пациента
      </li>
      <li class="specialists-list__item property-list__item">
        Дополнительный сервис коммуникации, позволяющий активно
        вовлекать пациента в процесс профилактики, лечения и реабилитации.
      </li>
    </ul>
  </div>
</template>

<style lang="scss">
.specialists {
  color: #60759d;
  background: rgba($color: #f1f2fa, $alpha: 0.4);
  position: relative;
  padding-bottom: 128px;

  &-title {
    margin-bottom: 30px;
  }

  &-list {
    font-weight: 600;
    padding-top: 81px;
    width: 580px;
    margin-left: 49%;

    &__item {
      width: 100%;
    }
  }
}

.img-scheme {
  background: url("../assets/scheme.png");
  background-repeat: no-repeat;
  width: 905px;
  height: 640px;
  position: absolute;
  top: -80px;
  left: 0;
}
</style>

