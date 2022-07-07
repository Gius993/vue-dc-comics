<template>
  <div class="container">
	<div class="click">
		<strong>SING-UP-NOW</strong>
	</div>
	<div class="social">
		<strong>FOLLOW US</strong>
		<div class="icon">
			<img src="../assets/img/footer-facebook.png" alt="iconsocial">
		</div>
			<div class="icon">
			<img src="../assets/img/footer-periscope.png" alt="iconsocial">
		</div>
			<div class="icon">
			<img src="../assets/img/footer-pinterest.png" alt="iconsocial">
		</div>
			<div class="icon">
			<img src="../assets/img/footer-twitter.png" alt="iconsocial">
		</div>
			<div class="icon">
			<img src="../assets/img/footer-youtube.png" alt="iconsocial">
		</div>
	</div>
  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	@import '../style/variables.scss';
	*{
		background-color: $brand_color_b;
	}
	.container{
		padding: 25px;
		display: flex;
		justify-content: space-around;
	}
	.click{
		text-align: center;
		padding: 10px;
		width: max-content;
		border: 2px solid $brand_color_e;
		color: white;
	}
	.social{
		display: flex;
		align-items: center;			
		color: $brand_color_e;
		strong{
			margin-right: 20px;
		}		
	}
	.icon{
		width: 30px;
		margin-right: 10px;
	}
</style>