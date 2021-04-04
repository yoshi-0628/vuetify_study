<template>
  <v-app>
    <v-app-bar
      app
      dark
      elevate-on-scroll
      scroll-target="#scrolling-techniques-7"
    >
    <v-app-bar-nav-icon></v-app-bar-nav-icon>
      <div class="d-flex align-center">

        <v-img
        :src="require('./assets/logo_transparent.png')"
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          width="200"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-heart</v-icon>
      </v-btn>

      <v-btn icon>
        <v-icon>mdi-dots-vertical</v-icon>
      </v-btn>

    </v-app-bar>
    <v-sheet
      id="scrolling-techniques-7"
      class="overflow-y-auto"
    >
      <v-main>
        <HelloWorld/>
        <HelloWorld/>
      </v-main>
    </v-sheet>

  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld';

export default {
  name: 'App',

  components: {
    HelloWorld,
  },

  data: () => ({
    //
  }),
};
</script>
