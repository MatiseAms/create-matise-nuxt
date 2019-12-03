<template>
	<section class="simple-content">
		<h1>Automatise Nuxt!</h1>
		<p class="font-italic">
			Powered by
			<a href="https://www.matise.nl/">Matise</a>
		</p>
	</section>
</template>

<style lang="scss">
@import '~gryd';
.simple-content {
	width: grid(12);
	margin: grid(2) auto;
	@media #{$small-only} {
		width: 100%;
		padding: 2rem;
	}
}
</style>
