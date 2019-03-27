<template>
	<div class="container">
		<div class="side-bar">
			<router-link to="/lib_questions">题库</router-link>
			<router-link to="/lib_resources">资源库</router-link>
			<router-link to="/lib_activities">活动库</router-link>
		</div>
		<div class="content"><router-view /></div>
	</div>
</template>

<script>
export default {
	name: 'Lib',
	data() {
		return {
			
		};
	}
};
</script>

<style>
</style>
