<template>
	<div id="contFooter">
		<MenuFooter />
        <SocialComp />
	</div>
</template>


<script>
import MenuFooter from "./ComponentsFooter/MenuFooter.vue";
import SocialComp from "./ComponentsFooter/SocialComp.vue";


export default {
	name: "FooterComp",
	components: {
		MenuFooter,
        SocialComp,
	},
};
</script>

<style scoped lang='scss'>
#contFooter{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
	background-image: url("../assets/img/footer-bg.jpg");


}
</style>