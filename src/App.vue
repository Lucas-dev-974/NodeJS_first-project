<template>
  <v-app>
    <v-app-bar dark app>
      <div class="d-flex align-center">
        <v-img alt="Nautilus Logo" contain src="./assets/nautilus-white.png" transition="scale-transition" width="150"/>
      </div>

      <v-spacer></v-spacer>
      <span class="mt-1 font-weight-medium">Community-wall</span>
      <v-spacer></v-spacer>

      <v-btn href="https://nautilus.fr" target="_blank" text>
        <span class="mr-2">Notre site</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <HelloWorld/>
    </v-main>
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
