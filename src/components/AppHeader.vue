<script setup lang="ts">
import { RouterLink } from 'vue-router';
import HeaderH1 from './ui/HeaderH1.vue';
</script>

<template>
	<header class="h-16 bg-teal-600">
		<div class="h-16 container grid grid-rows-[auto] grid-cols-1 content-center">
			<HeaderH1 class="al justify-self-start row-start-1 row-end-2 col-start-1 col-end-2" title="Простая форма" />
			<nav class="justify-self-center row-start-1 row-end-2 col-start-1 col-end-2">
				<RouterLink to="/">Форма</RouterLink>
				<RouterLink to="/preview">Превью</RouterLink>
			</nav>
		</div>
	</header>
</template>

