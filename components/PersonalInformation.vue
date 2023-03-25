<template>
  <div class="inform">
    <v-row>
      <img class="photo" width="27%" height="27%" src="../static/photo_2023-02-25_18-17-55.jpg" alt="photo">
      <v-col>
        <div class="name-text">
          <p><b>Фамилия:</b> Полевиков</p>
          <p><b>Имя:</b> Дмитрий</p>
          <p><b>Отчество:</b> Вячеславович</p>
          <p><b>Дата рождения:</b> 26.04.1989</p>
          <p><b>Место проживания:</b> город Кириши</p>
          <p><b>Гражданство:</b> Россия</p>
          <p><b>Готов к переезду:</b> Россия, готов к командировкам</p>
        </div>
        <div class="education">
          <h3 style="text-align: center;">Образование</h3>
          <div class="educationList">
            <ul class="educationlinks">
              <li>
                <p><b>Образовательное учереждение:</b> ГУАП</p>
                <p><b>Год выпуска:</b> 2011</p>
                <p><b>Специальность:</b> Инженер электромеханик</p>
              </li>
              <li>
                <p><b>Образовательное учереждение:</b> Synergy academy</p>
                <p><b>Год выпуска: </b> 2023</p>
                <p><b>Специальность: </b>Frontend-разработчик</p>
              </li>
            </ul>
          </div>
        </div>
        <h3 style="text-align: center; margin-top:15px;">Контакты</h3>
        <div class="contacts">
          <div class="contacts-body">
            <img class="contacts-body-img" width="40px" height="40px" src="../static/free-icon-chat-4542105.png" alt="telephone">
            <p class="contacts-body-text">+79046155339</p>
          </div>
          <div class="contacts-body">
            <img class="contacts-body-img" width="40px" height="40px" src="../static/free-icon-mail-4542220.png" alt="email">
            <p class="contacts-body-text">zmohaxz82@gmail.com</p>
          </div>
          <div class="contacts-body">
            <img class="contacts-body-img"
                 width="35px"
                 height="35px"
                 style="margin-right:5px"
                 src="../static/free-icon-telegram-2111646.png"
                 alt="telegram">
            <p class="contacts-body-text" style="margin-top:5px">@DPolevikov</p>
          </div>
          <div class="contacts-body">
            <img class="contacts-body-img"
                 width="35px"
                 height="35px"
                 style="margin-right:5px"
                 src="../static/free-icon-github-2111425.png"
                 alt="github"
            >
            <a href="https://github.com/Stranix89" class="contacts-body-text" style="margin-top:5px">https://github.com/Stranix89</a>
          </div>
        </div>
      </v-col>
    </v-row>
  </div>
</template>

<style scoped>
.inform {
background-color: #C7B9FF;
padding: 40px;
/*margin: 50px  0;*/
margin-top: 20px;
}

.photo {
  position: sticky;
  top: 85px;
  /*min-height: 2em;*/
}
.name-text {
border: 1px solid rgb(34, 128, 250);
padding: 15px;
}
.education {
    margin-top: 15px;
}
.educationList{
    border: 1px solid rgb(34, 128, 250);
    margin-top: 15px;
}
.educationlinks {
    margin-top: 10px;
}
.contacts {
    border: 1px solid rgb(34, 128, 250);
    margin-top: 15px;
}

.contacts-body {
    display: flex;
    padding-top: 20px;
    margin-left: 10px;
    margin-bottom: 5px;
}
.contacts-body-text {
    margin-left: 5px;
    margin-top: 10px;
}
</style>
