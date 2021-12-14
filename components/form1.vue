<template>
  <v-img
    src="https://images.pexels.com/photos/1342460/pexels-photo-1342460.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940"
  >
    <!-- <v-toolbar-side-icon class="white--text"></v-toolbar-side-icon>
    <v-icon right> </v-icon> -->

    <!-- <v-app-bar class="app-bars">
      <v-toolbar-title>CodeWohlig</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-btn class="button"> Deals </v-btn>

      <v-btn class="button1"> Courses </v-btn>

      <v-btn class="button2"> Log In </v-btn> -->

    <!-- <v-btn icon>
        <v-icon class="icon">mdi-dots-vertical</v-icon>
      </v-btn> -->
    <v-app-bar-nav-icon class="icon"></v-app-bar-nav-icon>
    <!-- </v-app-bar> -->
  </v-img>
</template>


<script>
export default {
  // data: () => ({
  //   links: ['Dashboard', 'Messages', 'Profile', 'Updates'],
  // }),
}
</script>
<style >
.bars {
  background-image: url('https://images.pexels.com/photos/1342460/pexels-photo-1342460.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=650&w=940');
  background-size: cover;
}
.app-bars {
  background-color: transparent;
}
.container {
  padding: 0;
  background-color: transparent !important;
}
.theme--light.v-app-bar.v-toolbar.v-sheet {
  background-color: transparent !important;
  color: white;
}
.button1 {
  background-color: transparent;
  color: white;
}
/* .icon {
  color: white;
  z-index: 4;
} */
.theme--light.v-btn.v-btn--icon {
  color: #fff;
}
</style>