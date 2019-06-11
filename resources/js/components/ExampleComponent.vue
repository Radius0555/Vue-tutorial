<template>
<div id="app">
Licznik: {{ counter }}
<button v-on:click="increment">+</button>
<button @click="decrement">-</button>
</div>
</template>

<script>
export default {
			data() {
				return {
					counter: 0
			};
		},
		methods: {
			increment(){
				this.counter = this.counter + 1;
			},
			decrement(){
				this.counter = this.counter -1;
			}
		}
	}	
</script>
