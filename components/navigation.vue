<template>
  <v-card class="mx-auto overflow-hidden" >
    <v-app-bar color="deep-purple" dark>
      <v-row>
        <v-col col="12" sm="4" class="">
          <v-toolbar-title>CodeWohlig</v-toolbar-title>
          <v-app-bar-nav-icon
            @click="drawer = true"
            class=""
          ></v-app-bar-nav-icon>
        </v-col>
      </v-row>
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" absolute temporary>
      <v-list nav dense>
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-title>Deals</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Courses</v-list-item-title>
          </v-list-item>
          <v-list-item>
            <v-list-item-title>Courses</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </v-card>
</template>

<script>
export default {
  data: () => ({
    drawer: false,
    group: null,
  }),
}
</script>