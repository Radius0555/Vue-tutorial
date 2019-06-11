<template>
<div id="app">
	<input v-model="text"/>
	<p v-if="text === ''">Wpisz coś</p>
	<p v-else>{{ text }}</p>
</div>
</template>

<script>
export default {
  data() {
    return {
      text: "",
    };
  }
}	
</script>
