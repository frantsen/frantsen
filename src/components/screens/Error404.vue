<template>
	<div id="error-404" @click="$router.push({name: 'home'})">
		<h1>404</h1>
		Click screen or tap to go Home.
	</div>
</template>

<script>
export default {
	name: 'error-404',
};
</script>

<style scoped>
#error-404 {
	padding-top: 30vh;
	text-align: center;
	cursor: crosshair;
}
</style>
