<template>
  <div>
    <v-app-bar app color="111111" dark flat class="px-8">
      <v-btn icon>
        <v-icon color="#A7121D">fas fa-dragon</v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')">Главна</v-btn>
      <v-btn text @click="scroll('tech')">Технологии</v-btn>
      <v-btn text @click="scroll('project')">Проекты</v-btn>
      <v-btn text @click="scroll('about')">Обо мне</v-btn>
      <v-btn text @click="scroll('contact')">Контакты</v-btn>
    </v-app-bar>
  </div>
</template>
<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>
<style>
</style>