<template>
    <Card outlined>
        <v-img v-bind:src="src" class="img"></v-img>
        <v-card-title>{{ title }}</v-card-title>
				<v-card-subtitle>{{ subtitle }}</v-card-subtitle>

    </Card>
</template>

<script>
export default{
    data(){
        return{
					src: require('/src/assets/library.jpg'),
					title: "図書館",
					subtitle: "大人から子供までみんなが本を楽しめる空間"
        }
    }
}
</script>

<style>
.img{
  height: 25vh;
}
</style>
