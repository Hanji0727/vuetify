<template>
    <Card outlined>
        <v-img 
          v-bind:src="src"
          class="img"></v-img>
        <v-card-title>{{ title }}</v-card-title>
				<v-card-subtitle>{{ subtitle }}</v-card-subtitle>

    </Card>
</template>

<script>
export default{
    data(){
        return{
					src: require('/src/assets/cafe.jpg'),
					title: "カフェ 〇〇",
					subtitle: "花巻の木材を使用したほっと一息つける場所"
        }
    }
}
</script>

<style>

</style>
