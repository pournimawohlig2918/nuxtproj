<template>
  <div class="bars">
    <!-- <v-toolbar-side-icon class="white--text"></v-toolbar-side-icon>
    <v-icon right> </v-icon> -->

    <v-app-bar class="app-bars">
      <v-toolbar-title>CodeWohlig</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon> D1 </v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon> C1 </v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon> L1 </v-icon>
      </v-btn>

      <!-- <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn> -->
      <v-app-bar-nav-icon></v-app-bar-nav-icon>
    </v-app-bar>

    <!-- <v-navs
        centered
        class="ml-n9"
        color="#880E"
        background-color="deep-purple accent-4"
      >
        <v-nav v-for="link in links" :key="link">
          {{ link }}
        </v-nav>
      </v-navs> -->
  </div>
</template>


<script>
export default {
  // data: () => ({
  //   links: ['Dashboard', 'Messages', 'Profile', 'Updates'],
  // }),
}
</script>
<style >
body {
  background-image: url(https://images.pexels.com/photos/1342460/pexels-photo-1342460.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940);
  /* background-color: pink; */
  background-size: cover;
}

/* .theme--light.v-navs > .v-navs-bar {
  background-color: transparent;
   color: white; 
}
.v-nav.v-nav {
   color: white; 
}
.theme--light.v-navs > .v-navs-bar .v-nav:not(.v-nav--active) {
   color: white; 
  text-align: 'center';
} */
</style>