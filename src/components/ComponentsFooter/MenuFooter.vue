<template>
	<div id="menuFooter">
		<div class="container">
			<div class="menu">
				<!-- Col 1 -->
				<div>
					<ul>
						<li>DC COMICS</li>

						<li>Characters</li>
						<li>Comics</li>
						<li>Movies</li>
						<li>TV</li>
						<li>Games</li>
						<li>Videos</li>
						<li>News</li>
					</ul>

					<ul>
						<li>SHOP</li>

						<li>Shop DC</li>
						<li>Shop DC Collectibles</li>
					</ul>
				</div>

				<!-- COl 2 -->
				<div>
					<ul>
						<li>DC</li>
						<li>Terms Of Use</li>
						<li>Privacy policy (New)</li>
						<li>Ad Choises</li>
						<li>Advrtaising</li>
						<li>Jobs</li>
						<li>Subscriptions</li>
						<li>Talent Workshops</li>
						<li>CPSC Certificates</li>
						<li>Tatings</li>
						<li>Shop Help</li>
						<li>Contact Us</li>
					</ul>
				</div>

				<!-- Col 3 -->
				<div>
					<ul>
						<li>SITES</li>
						<li>DC</li>
						<li>MAD Magazine</li>
						<li>DC Kids</li>
						<li>DC Universe</li>
						<li>DC Power Visa</li>
					</ul>
				</div>
			</div>

			<img src="../../assets/img/dc-logo-bg.png" alt="">

			
		</div>
	</div>
</template>


<script>
export default {
	name: "MenuFooter",
};
</script>

<style scoped lang='scss'>
#menuFooter {
	width: 70%;
	margin: auto;
	color: white;
	
}
.container{
	display: flex;
}
.container .menu {
	display: flex;
	padding: 25px;
}
ul {
	list-style: none;
	margin: 0 25px 25px;
}
ul li:first-child {
	font-size: 22px;
	font-weight: bold;
	padding-bottom: 20px;
}
img{
	position: absolute;
	left: 50%;
	transform: translatey(-100px);
}
</style>