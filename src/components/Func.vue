<template>
  <div class="function" id="function">
    <div class="function-background"></div>
    <div class="function-title">Функции приложения</div>
    <ul class="function-list">
      <li class="function-list__item function-list__item">
        <div class="function-list__item-circle function-list__item-circle--medicine"></div>Планирование графика приема лекарств
      </li>
      <li class="function-list__item">
        <div class="function-list__item-circle function-list__item-circle--siren"></div>Уведомление врача об исполнении назначений
      </li>
      <li class="function-list__item">
        <div class="function-list__item-circle function-list__item-circle--health"></div>Ведение дневника самочувствия
      </li>
      <li class="function-list__item">
        <div class="function-list__item-circle function-list__item-circle--smartwatch"></div>Удаленное предоставление измерений врачу
      </li>
      <li class="function-list__item">
        <div class="function-list__item-circle function-list__item-circle--conversation"></div>Общение с врачами через встроенный мессенджер
      </li>
      <li class="function-list__item">
        <div class="function-list__item-circle function-list__item-circle--facebook"></div>Получение уведомлений для выполнения назначений
      </li>
    </ul>
  </div>
</template>


<style lang="scss">
.function {
  background: #f5f8fd;
  color: #60759d;
  padding-bottom: 170px;

  &-background {
    background-image: url("../assets/back.jpg");
    background-repeat: no-repeat;
    background-position: top;
    height: 158px;

    position: absolute;
    width: 100%;
    min-width: 1900px;
  }

  &-title {
    width: 383px;
    margin: 0 auto;
    font-size: 36px;
    font-weight: 600;
    line-height: 54px;
    padding-top: 145px;
  }

  &-list {
    width: 1200px;
    margin: 0 auto;
    display: flex;
    flex-wrap: wrap;
    &__item {
      width: 33%;
      padding: 51px 88px 32px;
      text-align: center;
      font-size: 16px;
      line-height: 24px;
      font-weight: 600;

      &:last-child {
        padding: 51px 81px 32px;
      }

      &-circle {
        position: relative;
        width: 80px;
        height: 80px;
        border: 1px solid #c3e5f5;
        border-radius: 50px;
        margin: 0 auto;
        margin-bottom: 15px;
        &::before {
          content: "";
          position: absolute;
          display: block;
          background-repeat: no-repeat;
          width: 36px;
          height: 32px;
          left: calc(50% - 16px);
          top: calc(50% - 16px);
        }

        &--health {
          &::before {
            background-image: url("../assets/health.svg");
          }
        }

        &--medicine {
          &::before {
            background-image: url("../assets/medicine.svg");
          }
        }

        &--siren {
          &::before {
            background-image: url("../assets/siren.svg");
          }
        }

        &--smartwatch {
          &::before {
            background-image: url("../assets/smartwatch.svg");
          }
        }

        &--facebook {
          &::before {
            background-image: url("../assets/facebook.svg");
          }
        }

        &--conversation {
          &::before {
            background-image: url("../assets/conversation.svg");
          }
        }
      }
    }
  }
}
</style>
