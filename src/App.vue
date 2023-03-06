<template>
  <div>
    <v-app>
			<Cardlist></Cardlist>
    </v-app>
  </div>
</template>

<script>
import Hambargermenu from './components/menu/Hambargermenu.vue'
import Hambargermenu1 from './components/menu/Hambargermenu1.vue'

import Cardlist from './components/Cardlist.vue'

export default {
  components: { 
    Hambargermenu,
    Hambargermenu1,
    Cardlist
  },
  data() {
    return{
			
    }
  }
}
</script>

<style>

</style>
