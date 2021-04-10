<template>
  <div>
    <div>
      <h1>Здравствуйте!</h1>
    </div>
    <div class="container">
      <div class="text_p">
        <p>Выберите язык</p>
      </div>
      <div class="container_btn">
        <button class="container_btn_ru" type="button" onclick="ruregistration.vue">
          <img src="https://www.countryflags.com/wp-content/uploads/russia-flag-png-xl.png" alt="ru">
          <p class="container_btn_text_ru">
            Русский
          </p>
        </button>
      </div>
      <div>
        <button class="container_btn_kg" type="button" onclick="kgregistration.vue">
          <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/ba/Flag_of_Kyrgyzstan.png/1200px-Flag_of_Kyrgyzstan.png" alt="kg">
          <p class="container_btn_text_kg">
            Кыргызча
          </p>
        </button>
      </div>
    </div>
  </div>
</template>

<style>

/* кнопки */

body {
  position: relative;
  width: 375px;
  height: 812px;
  background-color: #fafafa;
}

.container {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0;
  position: absolute;
  width: 340px;
  height: 154px;
  left: 17px;
  top: 170px;
}

/* контейнер кнопок */

.container_btn {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 0;
  position: static;
  width: 340px;
  height: 115px;
  left: 0;
  top: 39px;
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 20px 0;
}

/* кнопки */

.container_btn_ru {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 23px 49px 23px 10px;
  position: static;
  width: 340px;
  height: 53px;
  left: 0;
  top: 0;
  background: #fff;
  box-shadow: 0 0 6px rgba(0, 0, 0, 0.06);
  border-radius: 5px;
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 9px 0;
}

.container_btn_kg {
  display: flex;
  flex-direction: row;
  align-items: center;
  padding: 23px 49px 23px 10px;
  position: static;
  width: 340px;
  height: 53px;
  left: 0;
  top: 62px;
  background: #fff;
  box-shadow: 0 0 6px rgba(0, 0, 0, 0.06);
  border-radius: 5px;
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 9px 0;
}

/* здравствуйте */
h1 {
  position: absolute;
  left: 115px;
  top: 102px;
  font-family: 'Times New Roman', Times, serif;
  font-style: normal;
  font-weight: bold;
  font-size: 22px;
  display: flex;
  line-height: 26px;
  align-items: center;
  text-align: center;
  letter-spacing: -0.408px;
  color: rgb(0, 0, 0);
}

/* выберите язык */
.text_p {
  position: static;
  left: 112.5px;
  top: 170px;
  font-family: 'Times New Roman', Times, serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: -0.408px;
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 20px 0;
  margin-top: 100px;
}

/* текст кнопок */

.container_btn_text_ru {
  position: static;
  width: 63px;
  height: 19px;
  left: 56px;
  top: 17px;
  font-family: 'Times New Roman', Times, serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  text-align: center;
  letter-spacing: -0.408px; /* интервал между букв */
  color: black;
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 0 10px;
}

.container_btn_text_kg {
  position: static;
  width: 75px;
  height: 19px;
  left: 56px;
  top: 17px;
  font-family: 'Times New Roman', Times, serif;
  font-style: normal;
  font-weight: normal;
  font-size: 16px;
  line-height: 19px;
  text-align: center;
  letter-spacing: -0.408px; /* интервал между букв */
  color: black;
  flex: none;
  order: 1;
  flex-grow: 0;
  margin: 0 10px;
}

/* флаг */

img {
  position: static;
  width: 36px;
  height: 23.35px;
  left: 10px;
  top: 14.82px;
  background: url(https://www.freepik.com/free-vector/illustration-russia-flag_2922294.htm#page=1&query=russia&position=10);
  border: 1px solid #f2f2f2;
  box-sizing: border-box;
  border-radius: 3px;
  flex: none;
  order: 0;
  flex-grow: 0;
  margin: 0 10px;
}
</style>
