<template>
  <v-container>
    <v-card>
      <v-card-title>
        <v-text-field v-model="yourName" label="Focus me" hint="Your name" />
      </v-card-title>
      <v-card-text> Your name is {{ yourName }} </v-card-text>
    </v-card>
  </v-container>
</template>

<script>
export default {
  data() {
    return {
      yourName: ""
    };
  }
};
</script>
