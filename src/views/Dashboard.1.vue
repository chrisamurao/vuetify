<template>
  <div class="dashboard">
    <h1 class="subheading grey--text">Dashboard</h1>
    <v-btn class="hidden-md-and-down">click me</v-btn>
    <v-btn color="success" class="hidden-md-and-up">no, click me</v-btn>
    <v-btn class="hidden-sm-only">click me, a plain button</v-btn>
    <v-container class="my-5">
      <v-layout row wrap>
        <!-- mobile-first approach -->
        <v-flex xs12 md6>
          <v-btn outline block class="primary">1</v-btn>
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outline block class="primary">2</v-btn>
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outline block class="primary">2</v-btn>
        </v-flex>
        <v-flex xs4 md2>
          <v-btn outline block class="primary">2</v-btn>
        </v-flex>
      </v-layout>

      <v-layout row wrap justify-space-around>
        <v-flex xs4 md3>
          <v-btn outline block class="success">1</v-btn>
        </v-flex>
        <v-flex xs4 md3>
          <v-btn outline block class="success">2</v-btn>
        </v-flex>
      </v-layout>
    </v-container>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>
