<template>
	<div id="app">
		<HeaderComp />
	</div>
</template>


<script>
import HeaderComp from "./components/HeaderComp.vue";

export default {
	name: "App",
	components: {
		HeaderComp,
	},
};
</script>

<style lang='scss'>
*{
	margin: 0;
    padding: 0;
    box-sizing: border-box;
    
}
#app{
	background-color: rgba(14, 14, 14, 1);
	height: 100vh;
	padding-top: 20px;
}
</style>