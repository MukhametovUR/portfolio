<template>
  <v-app :style="{ background: $vuetify.theme.themes.dark.background }">
    <Navbar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img
            src="/img/photo.png"
            contain
            max-height="500"
            class="photo"
          ></v-img>
        </v-col>
        <v-col cols="6" id="home">
          <h5 class="white--text text-darken-4 top">Привет, меня зовут Урал</h5>
          <h1 class="white--text">Фронтенд разрботчик</h1>
          <div class="white--text">
            В настоящее время работаю над проектом изучение иностранных
            языков.<br />
            который поможет желающим изучть новый иностранный язык или улучшить
            <br />
            знания изученного ранее. <br />
            В команде 7 специалистов: 2 - Бекенда, 4 - Фронтенда, 1- Тимлид
            <br />
            В команде гибкая система рзработки с приенение недельных спринтов,
            <br />
            которые обговариваются до и после выполнения.
          </div>
          <v-btn @click="scroll('contact')" tile color="#A7121D dark">
            Как связаться?</v-btn
          >
        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="tech">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-palette-swatch</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">QA, автотесты</h3>
                  <p class="grey--text ml-3 mt-6">
                    Покрытие продукта <br />
                    интеграционными,<br />
                    сквозными автотестами
                  </p>
                  <v-btn color="#A7121D" dark text>
                    подробнее
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon x-large class="ml-3" dark>mdi-shopping</v-icon>
                  <h3 class="white--text ml-3 mt-4">Фронтенд</h3>
                  <p class="grey--text ml-3 mt-6">
                    Разрботка клиентского <br />
                    интерфейса при помощи <br />
                    современного фреймворка
                  </p>
                  <v-btn dark text>
                    подробнее
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#A7121D" x-large class="ml-3"
                    >mdi-book-open-page-variant</v-icon
                  >
                  <h3 class="white--text ml-3 mt-4">Верстка сайтов</h3>
                  <p class="grey--text ml-3 mt-6">
                    Десктопная, адаптивная <br />
                    под планшет и <br />
                    мобильное устройство
                  </p>
                  <v-btn color="#A7121D" dark text>
                    подробнее
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>

              <v-col cols="12" class="mt-10">
                <h3 class="white--text py-6 position-center">
                  Стек технологий
                </h3>

                <div class="child2 mRight">
                  <v-row>
                    <stek-button>Postman</stek-button>
                    <stek-button>Cypress.io</stek-button>
                    <stek-button>Jusmine</stek-button>
                  </v-row>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <stek-button>git</stek-button>
                    <stek-button>Vue.js</stek-button>
                    <stek-button>JavaScript</stek-button>
                  </v-row>
                </div>
                <!-- <div class="child2 mRight">
                      <v-row>
                        <stek-button>Jira</stek-button>
                        <stek-button>Trello</stek-button>
                        <stek-button>Confluence</stek-button> 
                      </v-row>                       
                    </div> -->
                <div class="child2 mRight">
                  <v-row>
                    <stek-button>HTML5</stek-button>
                    <stek-button>CSS3</stek-button>
                    <stek-button>SASS</stek-button>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col style="text-align: center" id="project">
          <div class="white--text"><h2>Проекты</h2></div>
        </v-col>
        <v-row>
          <v-col md="3" offset-md="1" style="text-align: center">
            <v-card
              class="pa-2 py-12 content__block"
              outlined
              tile
              height="250px"
              color="#1E1E1E"
            >
              <v-img src="/img/helptense.png" contain max-height="200"></v-img>
              <v-btn
                color="white"
                dark
                text
                class="m1-n4"
                href="https://languageportalf.herokuapp.com/"
                target="_blank"
              >
                Изучение английского языка </v-btn
              ><br />
              <v-btn
                color="#A7121D"
                dark
                text
                class="m1-n4"
                href="https://languageportalf.herokuapp.com/"
                target="_blank"
              >
                Посмотреть
              </v-btn>
            </v-card>
          </v-col>
          <v-col md="3">
            <v-card
              class="pa-2 py-12 content__block"
              style="text-align: center"
              outlined
              tile
              height="250px"
              color="#1E1E1E"
            >
              <v-img src="/img/freshfood.png" contain max-height="200"></v-img>
              <v-btn
                color="white"
                dark
                text
                class="m1-n4"
                href="https://gilded-mooncake-3cb1cb.netlify.app/"
                target="_blank"
              >
                Правильное питание </v-btn
              ><br />
              <v-btn
                color="#A7121D"
                dark
                text
                class="m1-n4"
                href="https://gilded-mooncake-3cb1cb.netlify.app/"
                target="_blank"
              >
                Посмотреть
              </v-btn>
            </v-card>
          </v-col>
          <v-col md="3">
            <v-card
              class="pa-2 py-12 content__block"
              style="text-align: center"
              outlined
              tile
              height="250px"
              color="#1E1E1E"
            >
              <v-img src="/img/insurance.png" contain max-height="200" />
              <v-btn
                color="white"
                dark
                text
                class="m1-n4"
                href="https://glistening-dolphin-f52e64.netlify.app/"
                target="_blank"
              >
                Лендинг страховой компани </v-btn
              ><br />
              <v-btn
                color="#A7121D"
                dark
                text
                class="m1-n4"
                href="https://glistening-dolphin-f52e64.netlify.app/"
                target="_blank"
              >
                Посмотреть
              </v-btn>
            </v-card>
          </v-col>
        </v-row>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <v-row style="width: 100%; margin: 30px 0">
              <v-row
                style="
                  margin: 5px 15px;
                  border: 1px solid #fff;
                  border-radius: 10px;
                "
              >
                <v-col cols="3">
                  <h2 class="white--text">Образование</h2>
                </v-col>
                <v-col md="3">
                  <div class="white--text">УГАТУ</div>
                  <div class="white--text">
                    Специалист прикладной информатики
                  </div>
                  <div class="white--text">2013-2017</div>
                </v-col>
                <v-col md="6">
                  <p class="white--text">
                    Освоил базовые навоки архитектуры прикладных решений,
                    формирование локиги, составление и веденение технической
                    докуентции, формирование и выполнение требований ТЗ
                    программного продукта
                  </p>
                </v-col>
                <v-col cols="3"> </v-col>
                <v-col md="3">
                  <div class="white--text">GeekBrains</div>
                  <div class="white--text">Фронтент разработчик</div>
                  <div class="white--text">2021-2022</div>
                </v-col>
                <v-col md="6">
                  <p class="white--text">
                    Научился разрабатывать веб-приложение на Vue.js, строить
                    пользовательские интерфейсы благодаря компонентному подхода
                    фреймворка и способностью декомпозировть сложные структуры
                  </p>
                </v-col>
              </v-row>
            </v-row>
          </div>
          <div class="second" id="about">
            <v-row
              style="
                width: 100%;
                margin: 30px 0;
                display: flex;
                flex-wrap: wrap;
              "
            >
              <v-row
                style="
                  margin: 5px 15px;
                  border: 1px solid #fff;
                  border-radius: 10px;
                "
              >
                <v-col cols="3">
                  <h2 class="white--text">Обо мне</h2>
                </v-col>
                <v-col md="9">
                  <p class="white--text">
                    Веду активный образ жизни, изучаю английский язык, посещаю
                    митапы по применению прикладных решений. Изучаю техническую
                    документацию связанные с разрботкой и внедением
                    автоатизированных решений в бизнес предпрятия, либо
                    индививуальных предпринимателей
                  </p>
                </v-col>
              </v-row>
            </v-row>
          </div>
        </v-col>
      </v-row>
      <v-toolbar class="topTolbar" color="#111111" dark flat>
        <div
          style="
            position: absolute;
            margin-left: auto;
            margin-right: auto;
            left: 0;
            right: 0;
            text-align: center;
          "
        >
          <!-- <v-btn text @click="this.scroll('home')">Главная</v-btn>
                  <v-btn text>Проекты</v-btn>
                  <v-btn text>Обо мне</v-btn>
                  <v-btn text>Контакты</v-btn> -->
        </div>
      </v-toolbar>
    </v-container>
    <Footer id="contact" />
  </v-app>
</template>

<script>
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";
import StekButton from "@/components/StekButton";

export default {
  name: "Home",

  components: {
    Navbar,
    Footer,
    StekButton,
  },
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 150px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ce1d2a;
}
. {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 200px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
.title {
  align-self: center;
}
@media (max-width: 950px) {
  .content__block {
    max-width: 300px;
  }
  .first {
    display: none;
  }
  .photo {
    display: none;
  }
}
</style>
