<style>
.enabled{
	color: blue;
}
</style>
<template>
<div id="app">
<label :class="{ enabled: isEnabled }">
<input type="checkbox" v-model="isEnabled" />
Kliknij aby zmienić kolor!
</label>
</div>
</template>

<script>
export default {
			data() {
				return {
					isEnabled: true
			};
		}
	}	
</script>
