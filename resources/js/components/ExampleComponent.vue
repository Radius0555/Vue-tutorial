<template>
<div id="app">
<input v-model="name" />
<h1>{{ name }}</h1>
</div>
</template>

<script>
export default {
	data(){
		return {
			name: "Hello Mariolka ;)"
		}
	}
}	
</script>
