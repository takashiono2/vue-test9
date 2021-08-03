<template>
  <v-app>
    <v-app-bar
      app
      color="primary"
      dark
    >
      <div class="d-flex align-center">
        <v-img
          alt="Vuetify Logo"
          class="shrink mr-2"
          contain
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-logo-dark.png"
          transition="scale-transition"
          width="40"
        />

        <v-img
          alt="Vuetify Name"
          class="shrink mt-1 hidden-sm-and-down"
          contain
          min-width="100"
          src="https://cdn.vuetifyjs.com/images/logos/vuetify-name-dark.png"
          width="100"
        />
      </div>

      <v-spacer></v-spacer>

      <v-btn
        href="https://github.com/vuetifyjs/vuetify/releases/latest"
        target="_blank"
        text
      >
        <span class="mr-2">Latest Release</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <v-container>
        <v-row 
        class="blue lighten-4" 
        style="height: 450px;"
        justify="center" 
        align-content="center"
        >
          <v-col 
            cols=12 sm=10 md=8 lg=4 xl=3
            v-for="n in 3" :key="n">
            <v-card color="blue" outlined tile height=150></v-card>
          </v-col>
        </v-row>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
// import SaleGraph from './components/SaleGraph'

// export default {
//   components: {
//     // SaleGraph
//   },
//     mounted(){
//     console.log(this.$vuetify.breakpoint)
//   }
// };
</script>

<!--script>
// import HelloWorld from './components/HelloWorld';

// export default {
//   name: 'App',

//   components: {
//     HelloWorld,
//   },

//   data: () => ({
//     //
//   }),
// };
// </script>-->
