<template>
  <v-container
    class="portfolio"
    fluid
    style="min-height: 434px"
  >
    <v-fade-transition mode="out-in">
      <v-row>
        <v-col cols="6">
          <v-card>
            <v-img
              src="..//RockPaperScissors.jpg"
              class="portfolio-img"
              ></v-img>
              <v-card-title class="portfolio-img-text">
                <a href="https://github.com/Stranix89/Rock-Paper-Scissors">https://github.com/Stranix89/Rock-Paper-Scissors</a>
            </v-card-title>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card>
            <v-img
              src="..//cinema.jpg"
              height="467px"
              width="900px"
              cover
              class="portfolio-img"
            ></v-img>
            <v-card-title class="portfolio-img-text">
              <a href="https://github.com/Stranix89/react-cinema">https://github.com/Stranix89/react-cinema</a>
            </v-card-title>
          </v-card>
        </v-col>
        <v-col cols="15">
          <v-card>
            <v-img
              src="..//notebook.jpg"
              cover
              class="portfolio-img"
            ></v-img>
            <v-card-title class="portfolio-img-text">
              <a href="https://github.com/Stranix89/Notebook">https://github.com/Stranix89/Notebook</a>
            </v-card-title>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card>
            <v-img
              src="..//layout1.jpg"
              cover
              height="467px"
              class="portfolio-img"
            ></v-img>
            <v-card-title class="portfolio-img-text">
              <a href="https://github.com/Stranix89/Layout-1">https://github.com/Stranix89/Layout-1</a>
            </v-card-title>
          </v-card>
        </v-col>
        <v-col cols="6">
          <v-card>
            <v-img
              src="..//layout2.jpg"
              cover
              height="467px"
              class="portfolio-img"
            ></v-img>
            <v-card-title class="portfolio-img-text">
              <a href="https://github.com/Stranix89/Layout-1">https://github.com/Stranix89/Layout-1</a>
            </v-card-title>
          </v-card>
        </v-col>
      </v-row>
    </v-fade-transition>
  </v-container>
</template>

<style scoped>
.portfolio {
background-color: #C7B9FF;
padding: 40px;
margin: 50px  0;
}
.portfolio-img {
padding: 15px;
/*width: 900px;*/
}
.portfolio-img-text{
  text-align: center;
}
</style>
