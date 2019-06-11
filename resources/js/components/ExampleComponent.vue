<template>
<div id="app">
<a v-bind:href="togithub">{{ text }}</a>
<br>
<input v-model="togithub" />
</div>
</template>

<script>
export default {
	data(){
		return {
			text: "Do mojego githuba",
			togithub: "https://github.com/Radius0555/Vue-tutorial"
		}
	}
}	
</script>
