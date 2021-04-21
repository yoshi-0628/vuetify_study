<template>
  <v-container class="text-center">
    <v-row
      justify="center" align-content="center"
    >
      <v-col cols=auto v-for="n in 6" :key="n">
        <v-card
          elevation="1"
          max-width="444"
          width="444px"
        >
          <v-card-title>Card title</v-card-title>
          <v-card-subtitle>Subtitle text</v-card-subtitle>
          <v-card-text >
            Greyhound divisively hello coldly wonderfully marginally far upon excluding.
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
  export default {
    name: 'CommonCard',
  }
</script>
