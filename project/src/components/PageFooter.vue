<template>
  <div class="container">
		<div class="container-ul">
			<div class="li-container">
				<div class="list">
					<h3>Dc Comics</h3>
					<ul>
						<li>Cheachers</li>
						<li>Comic</li>
						<li>Movies</li>
						<li>TV</li>
						<li>Games</li>
						<li>Video</li>
						<li>News</li>

					</ul>
				</div>
				<div class="list">
					<h3>SHOP</h3>
					<ul>
						<li>Shop DC</li>
						<li>Shop DC Collecttables</li>
					</ul>
				</div>			
			</div>
			<div class="list">
					<h3>Dc</h3>
					<ul>
						<li>Team Of Use</li>
						<li>Privacy Pollcy</li>
						<li>Ad Choies</li>
						<li>Advesting</li>
						<li>Jobs</li>
						<li>Subscription</li>
						<li>Talent Workshop</li>
						<li>CPS Certificates</li>
						<li>Ratings</li>
						<li>Shop Help</li>
						<li>Contact Us</li>

					</ul>
				</div>
				<div class="list">
					<h3>SITES</h3>
					<ul>
						<li>DC</li>
						<li>MAD Magazine</li>
						<li>DC Kids</li>
						<li>DC Universe</li>
						<li>DC Powe Visa</li>

					</ul>
				</div>
		</div>
		<div class="img-container">
			<img src="../assets/img/dc-logo-bg.png" alt="img">
		</div>

  </div>
</template>

<script>

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
	@import '../style/variables.scss';

*{
	background-image: url('../assets/img/footer-bg.jpg');
	h3{
		color: white;
	}
	li{
		color: $brand_color_c;		
	}
	}
	.container{
		display: flex;
		justify-content: space-around;
		align-items: center;
	}
	.container-ul{
		display: flex;
	}
	.list{
		margin-left: 15px;
		h3{
			margin-bottom: 20px;
		}
		li{
			margin-bottom:10px ;
		}
	}
	.li-container{
		.list{
			margin-bottom: 10px;
		}
	}
</style>