<template>
  <v-container>
    <v-row class="text-center">
      <v-col cols="4">
        <v-img
          :src="require('../assets/logo.png')"
          class="my-3"
          contain
          height="200"
        />
      </v-col>
      <v-col cols="8">
        <CommonCard />
      </v-col>

    </v-row>
  </v-container>
</template>

<script>
  import CommonCard from './CommonCard';
  export default {
    name: 'HelloWorld',
    components: {
      CommonCard,
    },
    data: () => ({
      
    }),
  }
</script>
