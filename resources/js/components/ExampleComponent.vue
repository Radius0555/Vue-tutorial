<style>
.enabled{
	color: blue;
}
</style>
<template>
<div id="app">
<p class="static-class" :class="[isEnabled ? 'enabled' : null, someClass, dynamicClasses, {highlighted: isHighlighted}]">
Element, który ma je wszystkie!
</p>
</div>
</template>

<script>
export default {
			data() {
				return {
					someClass: 'some-weird-class',
					dynamicClasses: {
						first: true,
						second:false
					},
					isEnabled: true,
					isHighlighted: false,
			};
		}
	}	
</script>
