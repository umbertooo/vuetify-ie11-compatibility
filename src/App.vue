<template>
  <div id="app">
    <div class="header">
      The header should be placed above the datepicker.
    </div>
    <div class="content">
      <vuetify-app></vuetify-app>
    </div>
    <div class="footer">
      This footer should be placed below the datepicker.
    </div>
  </div>
</template>

<script>
import VuetifyApp from './components/vuetify-app';

export default {
  name: 'App',
  components: {
    VuetifyApp,
  },
};
</script>

<style>
.header {
  border-bottom: 2px solid black;
  background-color: #ccc;
  height: 30px;
}

.footer {
  border-top: 2px solid black;
  background-color: #ccc;
  height: 30px;
}

.application--wrap {
  /* this is the original css style from vuetify */
  min-height: 100vh;
}
</style>
