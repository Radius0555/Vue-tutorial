<template>
<div id="app">
<input type="number" v-model="number">
<p>Metoda: {{ fullName() }}</p>
</div>
</template>

<script>
export default {
			data() {
				return {
					firstName: "Radosław",
					lastName: "Foltyński",
					number: "7"
			};
		},
		methods: {
			fullName(){
				alert("Metoda załadowana!");
				return this.firstName + " " + this.lastName;
			}
		}
	}	
</script>
