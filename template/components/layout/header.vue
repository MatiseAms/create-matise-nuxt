<template>
<<<<<<< HEAD:template/components/main/header.vue
	<header class="header">
		<h2>{{ projectName }}</h2>
=======
	<header id="header" class="header">
		<h3>{{ projectName }}</h3>
>>>>>>> parent of 2dbfa8e... WIP:template/components/layout/header.vue
	</header>
</template>

<script>
import project from '~/package.json';
export default {
	data() {
		return {
			projectName: project.name
		};
	}
};
</script>

<style lang="scss">
.header {
	// Header styles
	position: fixed;
	top: 0;
	left: 0;

	width: 100%;
	text-align: center;
}
</style>
