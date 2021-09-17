<script setup>
	import { ref } from 'vue';

	let count = ref(0);

	function increment () {
		count.value++;
	}
</script>

<template>
	<div class='red'>It's red!</div>
	<button @click='increment'>{{ count }}</button>
</template>

<style scoped>
	.red {
		color: red;
	}
</style>
