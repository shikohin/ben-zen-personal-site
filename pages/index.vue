<template>
	<NuxtLayout>
		<div>
			<h1>Welcome to My Nuxt.js TypeScript Site!</h1>
			<p>{{ message }}</p>
			<button @click="incrementCounter">Increment Counter</button>
			<p>Counter: {{ counter }}</p>
		</div>
	</NuxtLayout>
</template>

<script lang="ts">
import { defineComponent, ref } from 'vue';

export default defineComponent({
name: 'IndexPage', // Optional, but good practice for debugging
setup() {
	const message = ref('This is a TypeScript component!');
	const counter = ref(0);

	const incrementCounter = () => {
	counter.value++;
	};

	return { message, counter, incrementCounter };
},
});
</script>
