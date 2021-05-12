<template>
  <v-app>
    <v-main>
      <Planes/>
    </v-main>
  </v-app>
</template>

<script>

import HelloWorld from './components/HelloWorld';

import Planes from './components/Planes';

export default {
  name: 'App',

  components: {
    HelloWorld,
    Planes,
  },

  data: () => ({
    //
  }),
};
</script>
