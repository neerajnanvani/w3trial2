<template>
  <v-app>
    <side-bar/>
    <v-main>
     
    </v-main>
  </v-app>
</template>

<script>

import SideBar from './components/SideBar.vue'
export default {
  name: 'App',

  components: {
    SideBar,
  },

  data: () => ({
    //
  }),
};
</script>


<style >
*{
font-family:'Poppins',sans-serif !important;
}
  
</style>