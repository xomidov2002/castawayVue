<template>
  <footer>
    <div class="container">
      <div class="cast">
        <img class="logo" src="../assets/images/logo.png" alt="logo" />
        <div class="scl">
          <i class="fab fa-instagram"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-facebook-f"></i>
        </div>
      </div>
      <ul class="menus">
        <li><a href="#">Home</a></li>
        <li><a href="#">About</a></li>
        <li><a href="#">Episodes</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
      <ul class="style">
        <li><a href="#">Style Guide</a></li>
        <li><a href="#">Instructions</a></li>
        <li><a href="#">Changelog</a></li>
        <li><a href="#">Credit</a></li>
        <li><a href="#">Powered by Webflow</a></li>
        <li><a href="#">Licenses</a></li>
      </ul>
      <div class="scls">
        <img src="../assets/images/sci-1.png" alt="" />
        <img src="../assets/images/sci-2.png" alt="" />
        <img src="../assets/images/sci-3.png" alt="" />
        <img src="../assets/images/sci-4.png" alt="" />
		<img src="../assets/images/sci-5.png" alt="" />
      </div>
    </div>
  </footer>
</template>

<script>
export default {};
</script>

<style lang="scss">
	footer{
		margin-bottom: 127px;
		.container{
			display: flex;
			justify-content: space-between;
			align-items: flex-start;
			.logo{
				margin-bottom: 26px;
				width: 223px;
			}
			.scl{
				font-size: 24px;
				color: #fff;
				display: flex;
				gap: 11px;
			}
			ul{
				display: flex;
				flex-direction: column;
				gap: 10px;
				li{
					a{
						font-weight: 400;
						font-size: 17px;
						line-height: 27px;
						color: #fff;
					}
				}
			}
			.scls{
				display: flex;
				gap: 18px;
				
			}
		}	
	}
</style>