<template>
	<section class="hero">
		<div class="container">
			<img class="main" src="../assets/images/main.jpg" alt="">
			<div class="level">
				<h2>Take your podcast to the <span class="underline">next</span> <span class="bold">level</span></h2>
				<div class="social">
					<p class="title">Listen on</p>
					<div class="scl">
						<img src="../assets/images/sci-1.png" alt="">
						<img src="../assets/images/sci-2.png" alt="">
						<img src="../assets/images/sci-3.png" alt="">
						<img src="../assets/images/sci-4.png" alt="">
						<img src="../assets/images/sci-5.png" alt="">
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
import "../assets/mainStyle.css"
export default {

}
</script>

<style lang="scss">
	.hero{
		padding: 40px 0 93px;
		.container{
			display: flex;
			gap: 60px;
			align-items: center;
			color: white;
			position: relative;
			.main{
				width: 650px;
				border-radius: 13px;
				position: relative;
				&::before{
					content: "";
					position: absolute;	
					inset: 0;
					top: 0;
					right : 0;
					background: url(../assets/images/IMAGE.svg) no-repeat center / cover;
				}
			}
			.level{
				position: relative;
				h2{
					font-weight: 400;
					font-size: 70px;
					line-height: 88px;
					letter-spacing: 3.2px;
					position: relative;
					.underline::before{
						content: "";
						position: absolute;
						inset: 0;
						bottom: 0;
						left: -450px;
						background: url(../assets/images/Vector.svg) no-repeat bottom
					}
					.bold{
						font-weight: 700;
					}
				}
				.social{
					position: absolute;
					bottom: -150px;
				}
				.social{
					.title{
						font-weight: 400;
						font-size: 15px;
						line-height: 24px;
						margin-bottom: 16px;
					}
					.scl{
						display: flex;
						gap: 18px;
					}
				}
			}
		}
	}
</style>