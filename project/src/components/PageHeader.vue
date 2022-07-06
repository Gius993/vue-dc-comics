<template>
	<div>
		<div class="container-header">
			<!--logo-->
			<div class="logo">
				<img src="../assets/img/dc-logo.png" alt="logo">
			</div>
			<!--list-->
			<div class="list-branding">
				<ul>
					<li v-for="link, index in menuList" :key="index">
						<a href="#">{{ link.text }}</a>
					</li>									
				</ul>
			</div>

		</div>
	</div>
</template>

<script>
	export default {
		name: "PageHeader",
		data(){
			return{
				menuList:[
					{
						text:'	CHARACTERS',
						url: '#',
						current: true
					},
						{
						text:'COMIC',
						url: '#',
						current: true
					},
						{
						text:'MOVIES',
						url: '#',
						current: true
					},
						{
						text:'TV',
						url: '#',
						current: true
					},
						{
						text:'GAMES',
						url: '#',
						current: true
					},
						{
						text:'COLLECTIBLE',
						url: '#',
						current: true
					},
						{
						text:'VIDEO',
						url: '#',
						current: true
					},
						{
						text:'FANS',
						url: '#',
						current: true
					},
						{
						text:'NEWS',
						url: '#',
						current: true
					},
						{
						text:'SHOP',
						url: '#',
						current: true
					},
				]
			}
		}
  }

</script>

<style lang="scss">
.logo{
	width: 100px;
	img{
		padding: 10px;
	}
}
.list-branding{
	a{
		color: black;		
	}
	ul{
		display: flex;		
	}
	li{
		padding-left: 20px;
		font-size: 16px;
	}
}
.container-header{
	height: 300px;
	display: flex;
	justify-content: space-around;
	align-items: center;
}
</style>