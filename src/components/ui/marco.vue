<template>
  <div>
    <v-row class="d-flex justify-around-space">
      <v-col v-for="(item, index) in items" :key="index">
        <v-card width="300" height="300">
          <v-card-text class="text-center">
            <h3>{{ item }}</h3>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>
  </div>
</template>

<script>
export default {
  props: {
    items: { type: Array },
  },
};
</script>

<style></style>
