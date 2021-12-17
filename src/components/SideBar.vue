<template>
  <div > 
      <v-navigation-drawer app class="red " height ="100%" width="15.4%">
      <v-list-item class=" my-12 mx-4">
        <v-list-item-content>
         <p class= "mt-12 company-title">Company<br>Name</p>
       
         
        </v-list-item-content>
      </v-list-item>

      

      <v-list
       
      >
        <v-list-item
          v-for="(item,index) in items"
          :key="index"
          link 
        >
          
          <v-list-item-content>
            <v-list-item-title>{{ item }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
  </div>
    

</template>

<script>
export default {
    data () {
      return {
        items: ['Home', 'Showcase', 'Services', 'Designers', 'Packages', 'Contact'],
        
      }
    },
}
</script>

<style scoped>

*{
    color:rgb(255, 255, 255) !important;
    
}

.company-title{
    font-size: 24px !important;
    line-height: 36px;
    font-weight:600 !important;

}
</style>