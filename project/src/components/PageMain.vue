<template>
	
	<div class="containerMain">
		<div class="main-top ">
			
			<div class="banner">
				<div class="click">
					<strong>CURRENT SERIES</strong>
				</div>
			</div>
			<div class="object-brend">

			</div>
		</div>
		
		<div class="main-bottom">
			<div class="card">
				<div class="image">
					<img src="../assets/img/buy-comics-digital-comics.png" alt="card">
				</div>
				<div class="text">
					Digital comic
				</div>
			</div>
				<div class="card">
				<div class="image">
					<img src="../assets/img/buy-comics-merchandise.png" alt="card">
				</div>
				<div class="text">
					Digital comic
				</div>
			</div>
				<div class="card">
				<div class="image">
					<img src="../assets/img/buy-comics-shop-locator.png" alt="card">
				</div>
				<div class="text">
					Digital comic
				</div>
			</div>
				<div class="card">
					<div class="image">
						<img src="../assets/img/buy-comics-subscriptions.png" alt="card">
					</div>
					<div class="text">
						Digital comic
					</div>
			</div>
				<div class="card">
					<div class="image">
						<img src="../assets/img/buy-dc-power-visa.svg" alt="card">
					</div>
					<div class="text">
						Digital comic
					</div>
			</div>
		</div>
	</div>

</template>

<script>

</script>

<style scoped lang="scss">
	@import '../style/variables.scss';
	
	.containerMain{
		width: 100%;
		color: white;
		.main-top{			
			background-color: $branc_color_d;
		}
		.main-bottom{
			background-color: $brand_color_a;
			padding: 50px;
			display: flex;
			justify-content: space-around;
			.card{
				display: flex;
				
				align-items: center;
			}
			.image{
				width: 50px;
			}
			.text{
				margin-left: 10px;
			}
		}
		.banner{
			background-image: url('../assets/img/jumbotron.jpg');
			width: 100%;
			height: 50vh;
			position: relative;
		.click{
			text-align: center;
			padding: 10px;
			width: max-content;
			background-color:$brand_color_a;
			color: white;
			position: absolute;
			bottom: -20px;
			left: 25%;
		}
	}
}
</style>