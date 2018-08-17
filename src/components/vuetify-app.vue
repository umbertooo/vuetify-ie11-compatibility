<template>
  <v-app id="my-app">
    <v-content>
      <v-container fluid>
        <v-layout column>
          <date-picker />
        </v-layout>
      </v-container>
    </v-content>
  </v-app>
</template>

<script>
import DatePicker from './date-picker';

export default {
  name: 'VuetifyApp',
  components: {
    DatePicker,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1,
h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
