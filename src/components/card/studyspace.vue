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
					src: require('/src/assets/studyspace.jpg'),
					title: "学習スペース",
					subtitle: "学びに集中できる空間"
        }
    }
}
</script>

<style>
.img{
  height: 25vh;
}
</style>
