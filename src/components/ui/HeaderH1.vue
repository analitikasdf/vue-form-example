<script setup lang="ts">
defineProps<{
	title: string;
}>();
</script>

<template>
	<h1 class="text-zinc-50">{{ title }}</h1>
</template>
