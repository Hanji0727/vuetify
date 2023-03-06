<template>
    <v-row justify="center">
      <v-col>
        <Library></Library>
      </v-col>
      <v-col>
        <Cafe></Cafe>
      </v-col>
      <v-col>
        <Studyspace></Studyspace>
      </v-col>
    </v-row>
</template>

<script>
import Library from './card/librarry.vue'
import Cafe from './card/cafe.vue'
import Studyspace from './card/studyspace.vue'

export default {
  components: { 
    Library,
    Cafe,
    Studyspace
  },
  data() {
    return{
    
    }
  }
}
</script>

<style>

</style>
