<template>
  <div>
    <h1>
      Регистрация
    </h1>
    <form action="Registration">
      <div class="name">
        <label for="">Имя</label>
        <input type="text">Ваше имя
      </div>
      <div>
        <label for=""> Фамилия</label>
        <input type="text"> Ваша фамилия
      </div>
      <div>
        <label for=""> Номер телефона</label>
        <input type="tel"> Ваш номер телефона
      </div>
      <div>
        <label for=""> Пароль </label>
        <input type="password"> input
      </div>
      <div>
        <label for=""> Повторить пароль</label>
        <input id="confirm_password" type="password" placeholder="Confirm Password" required> input
      </div>
    </form>
  </div>
</template>

<script>
const password = document.getElementById('password')
// eslint-disable-next-line camelcase
const confirm_password = document.getElementById('confirm_password')

function validatePassword () {
  // eslint-disable-next-line eqeqeq
  if (password.value != confirm_password.value) {
    confirm_password.setCustomValidity("Passwords Don't Match")
  } else {
    confirm_password.setCustomValidity('')
  }
}

password.onchange = validatePassword
confirm_password.onkeyup = validatePassword
</script>
