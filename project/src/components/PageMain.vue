<template>
	
	<div class="containerMain">
		<div class="main-top ">
			<div>
				<div class="banner">
					<div class="click">
						<strong>CURRENT SERIES</strong>
					</div>
				</div>
				<div class="object-brend">
					<ProductCard v-for="element, index in products " :key="index" :productDeatils="element" />				
				</div>
			</div>
				<div class="click">
					<strong>Load More</strong>
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
					DC MERCHANDAIS
				</div>
			</div>
			<div class="card">
				<div class="image">
					<img src="../assets/img/buy-comics-shop-locator.png" alt="card">
				</div>
				<div class="text">
					SUBSCRIPTION
				</div>
			</div>
				<div class="card">
					<div class="image">
						<img src="../assets/img/buy-comics-subscriptions.png" alt="card">
					</div>
					<div class="text">
						COMIC SHOP LOCATOR
					</div>
			</div>
				<div class="card">
					<div class="image">
						<img src="../assets/img/buy-dc-power-visa.svg" alt="card">
					</div>
					<div class="text">
						DC POWER VISA
					</div>
			</div>
		</div>
	</div>

</template>

<script>
   import ProductCard from "./ProductCard";
	
	export default{
		name: "ProductList",
		components:{
			ProductCard,
		},
		data() {
			return{
				products:[
					{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
					price: "$19.99",
					series: "Action Comics",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
					price: "$3.99",
					series: "American Vampire 1976",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
					price: "$16.99",
					series: "Aquaman",
					type: "graphic novel"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
					price: "$2.99",
					series: "Batgirl",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
					price: "$3.99",
					series: "Batman",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
					price: "$2.99",
					series: "Batman Beyond",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
					price: "$3.99",
					series: "Batman/Superman",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
					price: "$4.99",
					series: "Batman/Superman Annual",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
					price: "$5.99",
					series: "Batman: The Joker War Zone",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
					price: "$6.99",
					series: "Batman: Three Jokers",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
					price: "$4.99",
					series: "Batman: White Knight Presents: Harley Quinn",
					type: "comic book"
				},
				{
					thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
					price: "$16.99",
					series: "Catwoman",
					type: "graphic novel"
				}
			]
		};
	}
}
</script>

<style scoped lang="scss">
	@import '../style/variables.scss';
	
	.containerMain{
		width: 100%;
		color: white;
		.main-top{			
			background-color: $branc_color_d;
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
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
			background-size: cover;
			position: relative;
		.click{
			text-align: center;
			padding: 10px;
			width: max-content;
			background-color:$brand_color_a;
			color: white;
			position: absolute;
			bottom: -15%;
			left: 25%;
		}
	
	}
}
.object-brend{
	padding: 10%;
	display: flex;
	flex-wrap: wrap;
}

	.click{
		text-align: center;
		padding-left: 40px;
		padding-right: 40px;
		padding-top: 20px;
		padding-bottom: 20px;		
		width: max-content;
		background-color: $brand_color_a;
		color: white;
		display: inline-block;
		margin-bottom: 50px;
	}
</style>