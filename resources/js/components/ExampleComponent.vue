<template>
<div id="app">
<button @click="say('Hello Mariolka !')"> Powiedz hello mariolce :)</button>
<button @click="say('Papa Mariolka !')"> Powiedz papa Mariolce :)</button>
</div>
</template>

<script>
export default {
	methods: {
		say: function(msg) {
			alert(msg)
		}
	}
}
</script>


