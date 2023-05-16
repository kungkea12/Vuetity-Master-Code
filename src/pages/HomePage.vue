<template>
    <v-app :style="{background: $vuetify.theme.themes.dark.background}">
      <SideBar /> 
      <NavBar />
      <v-container>
        <v-row>
          <v-col cols="12" sm="9">
            <v-row>
              <v-col cols="12" sm="12">
                <ConTact />
              </v-col>
              <v-col cols="12" sm="12">
                <AgenDa />
              </v-col>
            </v-row>
          </v-col>
          <v-col cols="12" sm="3">
            <DocTor /> 
          </v-col>
        </v-row>
      </v-container>
    </v-app>
</template>

<script>
import AgenDa from '@/components/AgenDa.vue'
import ConTact from '@/components/ConTact.vue'
import NavBar from '../components/NavBar.vue'
import SideBar from '../components/SideBar.vue'
import DocTor from '@/components/DocTor.vue'
export default {
  components: { 
    SideBar, 
    NavBar, 
    ConTact, 
    AgenDa, 
    DocTor 
  },
}
</script>

<style>
</style>