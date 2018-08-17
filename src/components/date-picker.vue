<template>
  <v-flex xs12>
    <v-layout row wrap>
      <v-flex xs8>
        <v-card>
          <v-card-text>
            <v-date-picker
              v-model="picker"
              :landscape="landscape"
              :reactive="reactive">
            </v-date-picker>
          </v-card-text>
        </v-card>
      </v-flex>
      <v-flex xs4>
        <v-layout column wrap>
          <v-flex xs12 sm3>
            <v-checkbox v-model="landscape" hide-details label="Landscape"></v-checkbox>
          </v-flex>
          <v-flex xs12 sm3>
            <v-checkbox v-model="reactive" hide-details label="Reactive"></v-checkbox>
          </v-flex>
        </v-layout>
      </v-flex>
    </v-layout>
  </v-flex>
</template>

<script>
export default {
  name: 'DatePicker',
  data() {
    return {
      picker: null,
      landscape: false,
      reactive: false,
    };
  },
};
</script>
