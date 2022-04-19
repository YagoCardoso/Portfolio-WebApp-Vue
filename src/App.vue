<template>
  <body class="w3-light-grey">
    <div class="w3-content w3-margin-top" style="max-width: 1400px">
      <div style="background-color: #1257a7" class="w3-row-padding">
        <LeftColumn />
        <div class="w3-twothird">
          <ExperienceColumn />
          <AcademicFormation />
        </div>
      </div>
    </div>
    <ModalFooter />
  </body>
</template>

<script>
import LeftColumn from "./components/ColumnLeft.vue";
import ExperienceColumn from "./components/ExperienceColumn.vue";
import AcademicFormation from "./components/AcademicFormation.vue";
import ModalFooter from "./components/ModalFooter.vue";

export default {
  name: "App",
  components: {
    LeftColumn,
    ExperienceColumn,
    AcademicFormation,
    ModalFooter,
  },
};
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed");

@import "./assets/css/app.css";
html,
body,
h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Roboto", sans-serif;
}
</style>
