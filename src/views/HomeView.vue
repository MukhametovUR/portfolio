<template>
<v-app :style="{background: $vuetify.theme.themes.dark.background}">
    <Navbar />
    <v-container fluid>
        <v-row>
            <v-col cols="6">
                <v-img src="/img/photo.png" contain max-height="500"></v-img>
            </v-col>
            <v-col cols="6">
              <h5 class="white--text text-darken-4 top">Привет, меня зовут Урал</h5>
              <h1 class="white--text">Фронтенд разрботчик, QA</h1>
              <p class="white--text">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facilis repudiandae nulla ad voluptatem quam repellat optio aut consequatur totam at!
              </p>
              <v-btn tile color="#A7121D dark">Обо мне</v-btn>
            </v-col>
            <v-col cols="12" class="padd">
              <div class="first" id="project">
                <v-row>
                  <v-col cols="12">
                    <div class="child bgColor1">
                      <v-icon color="#A7121D" x-large class="ml-3"
                        >mdi-palette-swatch</v-icon>
                      <h3 class="white--text ml-3 mt-4">QA, автотесты</h3>
                      <p class="grey--text ml-3 mt-6">
                       Покрытие продукта <br /> интеграционными  сквозными <br />автотестами
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
                        Текст
                      </p>
                      <v-btn dark text>
                        подробнее
                        <v-icon right>mdi-arrow-right</v-icon>
                      </v-btn>
                    </div>
                    <div class="child bgColor1">
                      <v-icon color="#A7121D" x-large class="ml-3">mdi-book-open-page-variant</v-icon>
                      <h3 class="white--text ml-3 mt-4">Верстка сайтов</h3>
                      <p class="grey--text ml-3 mt-6">
                          Текст.
                      </p>
                       <v-btn color="#A7121D" dark text>
                        подробнее
                        <v-icon right>mdi-arrow-right</v-icon>
                      </v-btn>
                    </div>
                  </v-col>
                  <v-col cols="12" class="mt-10">
                    <div class="child1">
                      <h1 class="white--text mt-4">Стек технологий</h1>
                    </div>
                    <div class="child2 mRight">
                      <v-row>
                       <stek-button>HTML5</stek-button>
                       <stek-button>CSS3</stek-button>
                       <stek-button>JAVASCRIPT</stek-button>
                      </v-row>
                    </div>
                   
                    <div class="child2 mRight">
                      <v-row>
                        <stek-button>Vue.js</stek-button>
                        <stek-button>NPM</stek-button>
                        <stek-button>YARN</stek-button>                        
                      </v-row>
                    </div>
                      <div class="child2 mRight">
                      <v-row>
                        <stek-button>GIT</stek-button>
                        <stek-button>FIGMA</stek-button>
                        <stek-button>YARN</stek-button> 
                      </v-row>                       
                    </div>
                     <div class="child2 mRight">
                      <v-row>
                        <stek-button>JIRA</stek-button>
                        <stek-button>CONFLUENCE</stek-button>
                        <stek-button>YARN</stek-button> 
                      </v-row>                       
                    </div>

                  </v-col>
                </v-row>
              </div>
            </v-col>
            <v-col md="3" offset-md="3" id="about">
              <h4 class="white--text">FEATURED PROJECTS</h4>
              <p class="white--text">Lorem ipsum dolor sit</p>
            </v-col>
            <v-col md="3" class="text-end">
              <v-btn tile color="#A7121D" dark>View all</v-btn>
            </v-col>
            <v-col 
              md="3" 
              offset-md="3">
              <v-card 
              class="pa-2 py-12" 
              outlined 
              tile 
              height="250px" 
              color="#1E1E1E"
            >
                <v-img src="/img/posts.png" contain></v-img>
              </v-card>
            </v-col>
             <v-col md="3">
              <v-card 
                class="pa-2 py-12" 
                outlined 
                tile 
                height="250px" 
                color="#1E1E1E"
              >
                <v-img src="/img/1.png" contain></v-img>
              </v-card>
            </v-col>
             <v-col md="3" offset-md="3">
              <v-btn color="white" dark text class="m1-n4"
                href="https://vue3project.herokuapp.com/"
                target="_blank"
              >
                Posts
              </v-btn><br />
              <v-btn color="#A7121D" dark text class="m1-n4"
                href="https://vue3project.herokuapp.com/"
                target="_blank"
              >
                know more
              </v-btn>
              <v-icon right color="#A7121D">mdi-arrow-right</v-icon>
            </v-col>
             <v-col md="3">
              <v-btn color="white" dark text class="m1-n4">
                Foodasa
              </v-btn><br />
              <v-btn color="#A7121D" dark text class="m1-n4">
                know more
              </v-btn>
              <v-icon right color="#A7121D">mdi-arrow-right</v-icon>
            </v-col>
            <v-col 
              md="3" 
              offset-md="3">
              <v-card 
              class="pa-2 py-12" 
              outlined 
              tile 
              height="250px" 
              color="#1E1E1E"
            >
                <v-img src="/img/photo.png" contain></v-img>
              </v-card>
            </v-col>
             <v-col md="3">
              <v-card 
                class="pa-2 py-12" 
                outlined 
                tile 
                height="250px" 
                color="#1E1E1E"
              >
                <v-img src="/img/1.png" contain></v-img>
              </v-card>
            </v-col>
            <v-col cols="12" class="padd topInverse">
               <div class="second">
                  <div class="secondchild1" id="contact">
                    <v-row>
                      <v-col cols="7">
                        <h1 class="white--text">
                          Текст
                        </h1>
                        <p class="grey--text">
                         Текст <br />
                        </p>
                      </v-col>
                      <v-col cols="5">
                        <v-btn tile color="#A7121D" dark class="mt-16">
                          Контакты
                        </v-btn>
                      </v-col>
                    </v-row>
                  </div>
                </div>
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
                  <v-btn text>Главная</v-btn>
                  <v-btn text>Проекты</v-btn>
                  <v-btn text>Обо мне</v-btn>
                  <v-btn text>Контакты</v-btn>

                  </div>
                </v-toolbar>
            </v-col>
        </v-row>
    </v-container>
    <Footer />
</v-app>
</template>

<script>
  import Navbar from '@/components/Navbar'
  import Footer from '@/components/Footer'
  import StekButton from '@/components/StekButton'


  export default {
    name: 'Home',

    components: {
      Navbar,
      Footer,
      StekButton
    },
  }
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
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
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
.child1 {
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
</style>
