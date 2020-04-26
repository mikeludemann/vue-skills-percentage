<template>
	<div class="home">
		<img alt="Vue logo" src="../assets/logo.png">
		<HelloWorld msg="Welcome to Your Vue.js App"/>
		<circlePercentage :percentage="57" color="red" :dark="false"/>
		<skillsPercentage :percentage="57"/>
	</div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue';
import circlePercentage from '@/components/circle-percentage.vue';
import skillsPercentage from '@/components/skills-percentage.vue';

export default {
	name: 'Home',
	components: {
		HelloWorld,
		circlePercentage,
		skillsPercentage
	}
}
</script>
