<template>
  <div>
    <v-app-bar 
      app
      class="green lighten-2"
      clipped-left>
      <v-app-bar-nav-icon @click.stop="drawer = !drawer"></v-app-bar-nav-icon>
      <v-app-bar-title>Title is here</v-app-bar-title>
    </v-app-bar>

    <v-navigation-drawer
      app
      v-model="drawer"
      clipped
      >
        
        <v-list>
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-bookshelf</v-icon>
            </v-list-item-icon>
            <v-list-item-title>library</v-list-item-title>
          </v-list-item>
        </v-list>

        <v-list>
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-coffee</v-icon>
            </v-list-item-icon>
            <v-list-item-content>cafe</v-list-item-content>
          </v-list-item>
        </v-list>

        <v-list>
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-pen</v-icon>
            </v-list-item-icon>
            <v-list-item-content>study</v-list-item-content>
          </v-list-item>
        </v-list>

        <v-list>
          <v-list-item>
            <v-list-item-icon>
              <v-icon>mdi-phone</v-icon>
            </v-list-item-icon>
            <v-list-item-content>contact</v-list-item-content>
          </v-list-item>
        </v-list>
    </v-navigation-drawer>
    
    
      
  </div>
</template>

<script>
export default {
  date(){
    return{
      drawer: null
    }
  },
  props: {
    
  },
}
</script>

<style scoped>

</style>
