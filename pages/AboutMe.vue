
import AboutCarousels from '~/components/AboutCarousels.vue';
import AboutCarousel from '~/components/aboutCarousel.vue';

<template>
  <v-col>
    <div class="about">
      <v-col>
        <div class="about-text">
          <br><br>
          <b>Личные и профессиональные качества:</b><br>
          <ul>
            <li>
              Дисциплинированный
            </li>
            <li>
              Коммуникабельный
            </li>
            <li>
              Быстрро адаптируюсь
            </li>
            <li>
              Уважаю свое и чужое время, поэтому работу стараюсь выполнить качественно и в срок
            </li>
            <li>
              Люблю учиться и узнавать новое
            </li>
            <li>
              Умею высказывать аргументированно свое мнение
            </li>
            <li>
              Спокойно воспринимаю критику
            </li>
            <li>
              Умению организовывать работу группы людей
            </li>
            <li>
              Высокая работоспособность
            </li>
            <li>
              Умение быстро реагировать в сложных ситуациях
            </li>
            <li>
              Высокая обучаемость и восприимчивость
            </li>
            <li>
              Широкий технологический кругозор
            </li>
          </ul>
          <br><br>
          <b>Хобби:</b>
          <ul>
            <li>
              Книги
            </li>
            <li>
              Копаться в технике
            </li>
            <li>
              Съемка с квадрокоптера
            </li>
            <li>
              История
            </li>
            <li>
              Природа
            </li>
          </ul>
        </div>
      </v-col>
    </div>
    <AboutCarousel />
  </v-col>
</template>

<style scoped>
.about {
background-color: #C7B9FF;
padding: 40px;
margin: 50px  0;
}
.about-text {
border: 1px solid rgb(34, 128, 250);
padding: 15px;
}
.about-text p::first-letter {
  color: rgb(141, 1, 160);
}
</style>
