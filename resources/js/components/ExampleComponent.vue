<template>
<div id="app">
<ul>
<h2>Pieski:</h2>
<li v-for="(dog, index) in dogs">
{{ index }} {{ prefix }} {{ dog }}
</li>
</ul>
</div>
</template>

<script>
export default {
  data() {
    return {
		prefix: " => ",
		dogs: ["Azorek", "Kira", "Neruś"]
    };
  }
}	
</script>
