<template>
  <div class="container">
		<div class="container-ul">
			<div class="li-container">
				<div class="list">
					<h3>Dc Comics</h3>
					<ul>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>

					</ul>
				</div>
				<div class="list">
					<h3>Dc Comics</h3>
					<ul>
						<li>Cheachers</li>
						<li>Cheachers</li>
					</ul>
				</div>			
			</div>
			<div class="list">
					<h3>Dc Comics</h3>
					<ul>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>

					</ul>
				</div>
				<div class="list">
					<h3>Dc Comics</h3>
					<ul>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>
						<li>Cheachers</li>

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
	}
	.li-container{
		.list{
			margin-bottom: 10px;
		}
	}
</style>