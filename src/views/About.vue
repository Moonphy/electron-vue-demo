<template>
	<div class="section">
		<h1 class="title is-4">About</h1>
		<RouterLink class="button is-primary" to="home">
			<i class="material-icons">Home</i>
			<span>Home</span>
		</RouterLink>

		<h2 class="subtitle is-4">System Information</h2>
		<br />
	</div>
</template>

<script>
// import SystemInformation from '../components/SystemInformation.vue'

export default {
	name: 'About',
	components: {},
}
</script>

<style>
.block.has-text-centered figure {
	margin: 0 auto;
}
</style>
