<template>
	<div id="app">
		<HeaderComp />
		<ContentComp />
		<MainMenu />
		<FooterComp />
	</div>
</template>


<script>
import HeaderComp from "./components/HeaderComp.vue";
import ContentComp from "./components/ContentComp.vue";
import MainMenu from "./components/MainMenu.vue";
import FooterComp from "./components/FooterComp.vue";




export default {
	name: "App",
	components: {
		HeaderComp,
		ContentComp,
		MainMenu,
		FooterComp,
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