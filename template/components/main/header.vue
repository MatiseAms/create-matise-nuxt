<template>
	<header class="header">
		<h3>{{ projectName }}</h3>
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
@import '~tools';

.header {
	padding: 3rem;
}
</style>
