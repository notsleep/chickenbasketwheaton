<template>
  <v-app>
    <Spa/>
  </v-app>
</template>

<script>
import Spa from './views/Spa';

export default {
  name: 'App',

  components: {
    Spa,
  },

  data: () => ({
    //
  }),
};
</script>
