<script setup lang="ts">
const route = useRoute();

// @ts-ignore
const query = computed(() => new URLSearchParams(route.query).toString());
</script>

<template>
	<div>
		Home page: {{ query }}

		<Button>Button</Button>
	</div>
</template>
