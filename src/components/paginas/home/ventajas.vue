<template>
  <div>
    <v-container>
      <v-card flat="">
        <v-card-text class="text-center">
          <h1>
            VENTAJAS DE VUE
          </h1>
        </v-card-text>
        <v-card-text>
          <v-card>
            <Marco :items="ventajas"></Marco>
          </v-card>
        </v-card-text>
        <v-btn color="primary" @click="ventajas.push('a')">botn home</v-btn>
      </v-card>
    </v-container>
  </div>
</template>

<script>
import Marco from "@/components/ui/marco";
export default {
  components: {
    Marco,
  },
  data: () => ({
    ventajas: ["flexible", "sencillo", "elegante"],
  }),
};
</script>

<style></style>
