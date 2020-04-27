<template>
  <v-app>
    
    <v-content>
      <Login></Login>
      <HelloWorld/>
      <Home></Home>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from '@/components/HelloWorld';
import Home from '@/views/Home';
import Login from '@/components/Login';
export default {
  name: 'App',

  components: {
    HelloWorld,
    Login,
    Home,
  },

  data: () => ({
    //
  }),
};
</script>
