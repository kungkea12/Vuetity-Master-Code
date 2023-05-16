<template>
    <v-app-bar color="white" app dark flat>
      <v-icon color="black">fas fa-long-arrow-alt-left</v-icon>
      <h4 class="black--text ml-3">Master Code</h4>
      <v-spacer></v-spacer>
      <h4 class="green--text text--lighten-2">New Developer</h4>
      <v-icon x-small color="#42b883" class="ml-2 mr-2">fas fa-caret-down</v-icon>
      <v-btn color="#42b883" class="withoutupercase">
        <v-icon left>fas fa-plus</v-icon> New Project
      </v-btn>
      <v-badge dot overlap color="green" class="ml-3 mr-2" dark>
        <v-avatar tile color="#e5f1ff">
          <v-icon color="#42b883">fas fa-bell</v-icon>
        </v-avatar>
      </v-badge>
      <v-avatar tile color="#e5f1ff">
        <v-img src="p.png"></v-img>
      </v-avatar>
    </v-app-bar>
</template>

<script>
export default {

}
</script>

<style>
  .v-btn.withoutupercase {
    text-transform: none !important;
  }
</style>