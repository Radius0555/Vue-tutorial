<template>
<div id="app">
	<input v-model="text"/>
	<p v-show="text === ''">Wpisz coś</p>
	<p v-show="text !== ''">Dzięki!</br>{{ text }}</p>
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
