<template>
	<div id="SocialCont">
		<div class="container">
			<a href="#">SIGN-UP NOW!</a>

			<div>
				<span>FOLLOW US</span>
				<div>
					<span>
						<img
							src="../../assets/img/footer-facebook.png"
							alt="Alt"
						/>
					</span>
                    
					<span>
						<img
							src="../../assets/img/footer-twitter.png"
							alt="Alt"
						/>
					</span>

					<span>
						<img
							src="../../assets/img/footer-youtube.png"
							alt="Alt"
						/>
					</span>

					<span>
						<img
							src="../../assets/img/footer-pinterest.png"
							alt="Alt"
						/>
					</span>

					<span>
						<img
							src="../../assets/img/footer-periscope.png"
							alt="Alt"
						/>
					</span>
				</div>
			</div>
		</div>
	</div>
</template>


<script>
export default {
	name: "SocialComp",
	components: {},
};
</script>

<style scoped lang='scss'>
#SocialCont {
	width: 100%;
	background-color: rgba(48, 48, 48, 1);
	position: relative;
	z-index: 1;
}
.container a{
	text-decoration: none;
	color: white;
	border: 2px solid rgba(2, 130, 249, 1);
	padding: 20px;
}
.container {
	width: 70%;
	margin: auto;
	padding: 30px;
	display: flex;
	justify-content: space-between;
	align-items: center;
}
.container > div {
	display: flex;
	justify-content: space-between;
	align-items: center;
}
.container > div span {
	margin-right: 40px;
	color: rgba(2, 130, 249, 1);
	font-weight: bold;
	font-size: 22px;
}
.container > div > div > span {
	margin: 0 10px;
}
</style>