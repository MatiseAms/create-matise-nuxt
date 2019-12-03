<template>
	<header class="header">
		<h2>{{ projectName }}</h2>
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
	padding: 3rem;
}
</style>
