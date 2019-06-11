<template>
<div id="app">
<a v-bind="linkGit">{{ text }}</a>
<br>
</div>
</template>

<script>
export default {
	data(){
		return {
			text: "Do mojego githuba",
			linkGit: {
				href: "https://github.com/Radius0555/Vue-tutorial",
				title: "Kliknij!"
			}
		}
	}
}	
</script>
