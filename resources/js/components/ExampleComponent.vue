<template>
<div id="app">
<ul>
<h2>Pieski:</h2>
<li v-for="dog in dogs">
{{ dog }}
</li>
</ul>
</div>
</template>

<script>
export default {
  data() {
    return {
	  dogs: ["Azorek", "Kira", "Neruś"]
    };
  }
}	
</script>
