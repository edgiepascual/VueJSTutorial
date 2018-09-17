<template>
	<div class="about">
		<h1> Hello {{ their_name }}, This is an about page </h1>
	</div>
</template>

<script>
	export default {
		data() {
			return {
				their_name: this.$route.params.name
			}
		}
	}
</script>

<style scoped>

</style>