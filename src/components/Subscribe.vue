<template>
  <div class="subscribe">
    <div class="subscribe-title">Получите бесплатный доступ к «Дневнику здоровья»</div>
    <div
      class="subscribe-desc"
    >Оставьте свою электронную почту и вы узнаете о запуске данного сервиса первым</div>
    <div class="subscribe-form">
      <input class="form__input" placeholder="Ваш E-mail" type="mail" />
      <div class="btn btn--red btn__form">Отправить</div>
    </div>
  </div>
</template>

<style lang="scss">
.form__input {
  border: 1px solid #4f699b;
  border-radius: 100px;
  outline: none;
  width: 360px;
  padding-left: 15px;
  background: rgba($color: #e2eaf7, $alpha: 1);
}

.subscribe {
  color: #60759d;
  background: rgba($color: #e2eaf7, $alpha: 1);
  padding-bottom: 160px;
  &-title {
    width: 942px;
    margin: 0 auto;
    font-weight: 600;
    font-size: 34px;
    line-height: 54px;
    padding-top: 138px;
    margin-bottom: 40px;
  }

  &-desc {
    font-size: 24px;
    line-height: 36px;
    width: 573px;
    margin: 0 auto;
    text-align: center;
  }

  &-form {
    width: 560px;
    display: flex;
    justify-content: space-between;
    margin: 0 auto;
    margin-top: 54px;
  }
}
</style>

