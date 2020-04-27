<template>
  <div class="home">
    <img alt="Vue logo" src="@/assets/logo.png" />
    <h2>Este es el Home</h2>
<v-btn @click="" color="green" dark>
  <v-icon>mdi-close</v-icon> prueba
</v-btn>
<v-btn color="success" dark large fab> 
  <v-icon>mdi-pencil</v-icon>
</v-btn>
    <Intro></Intro>
    <Ventajas></Ventajas>
  </div>
</template>

<script>
// @ is an alias to /src
import Intro from "@/components/paginas/home/intro.vue";
import Ventajas from "@/components/paginas/home/ventajas";
import HelloWorld from "@/components/HelloWorld.vue";

export default {
  name: "Home",
  components: {
    Intro,
    Ventajas,
    HelloWorld,
  },
  data: () => ({
    ventajas: ["flexible", "sencillo", "elegante"],
  }),
};
</script>
