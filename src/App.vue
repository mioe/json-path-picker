<script setup>
import { onMounted } from 'vue'

onMounted(() => {
	console.log('🦕 onMounted')
})
</script>

<template>
	<main class="flex flex-col p-8">
		<header class="flex flex-col gap-1 font-mono">
			<h1 class="text-xl">
				json-path-picker
			</h1>
			<p>hello world</p>
		</header>
	</main>
</template>
