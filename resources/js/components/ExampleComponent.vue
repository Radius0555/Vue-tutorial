<template>
<div id="app">
<ul>
<h2>Moje dane:</h2>
<li v-for="(quality, My, index) in Mys">
{{ My }} => {{ quality }}
</li>
</ul>
</div>
</template>

<script>
export default {
  data() {
    return {
		Mys: {
			"first name": "Radosław",
			"last name": "Foltyński",
			"age": "28 lat"
		}
	};
  }
}	
</script>
