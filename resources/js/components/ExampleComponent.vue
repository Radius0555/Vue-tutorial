<template>
<div id="app">
<input v-model="liczba" />
<h1>{{ name + liczba*2 }}</h1>
</div>
</template>

<script>
export default {
	data(){
		return {
			name: "Hello Mariolka ;) ",
			liczba: 2,
		}
	}
}	
</script>
