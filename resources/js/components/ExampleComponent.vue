<template>
<div id="app">
<ul>
<li v-for="(quality, table) in Table">
{{ table }}
<ul>
	<li v-for="(dawaj, table) in quality">
		{{ dawaj }}
	</li>
</ul>
</li>
</ul>
</div>
</template>

<script>
export default {
  data() {
    return {
		Table: {
		Fruits: ["Jabłko", "Gruszka"],
		Drinkables: ["Woda", "Kawa"],
		}
	};
  }
}	
</script>
