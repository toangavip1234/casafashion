# casafashion
<!doctype html>
<html>
<head>
	<style>
		/*==header==*/
		
		#header>.logo{
			position: relative;							/*==Logo==*/
			top: 20px;
			left: 20px;
		}
		#header{width: 1500px;
			height: 200px;
			background-image: url("../pic/32132.png");				/*==Hình header==*/
		}
		.search-box{
    position: absolute;
    top: 61px;
    left: 456px;
    transform: translate(-50%,-50%);					/*==Thanh tìm kiếm==*/
    background: #FFB802;
    height: 40px;
    border-radius: 40px;
    padding: 10px;
    align-content: center;
		}
		.search-btn{
			color: #0084FF;
			float: right;
			width: 40px;
			height: 40px;
			border-radius: 50%;
			background: #F0F0F0;
			display: flex;
			justify-content: center;
			align-items: center;
			
		}
		.search-txt{
			border: none;
			background: none;
			outline: none;
			float: left;
			padding: 0;
			color:white;
			font-size: 16px;
			transition: 0.4s;
			line-height: 40px;
			width: 0px;
			
		}
		.search-box:hover > .search-txt{
			width: 240px;
			padding:  0 6px;						/*==Thanh tìm kiếm==*/
		}
		.medi{										/*==Mạng xh==*/
			width: 30px;
			height: 30px;
			display: grid;
		}
		.medi:hover{
			width: 40px;
			height:40px;
			box-shadow: 3px 3px 3px 0px gray;
			transition: 1s all ease;				/*==Mạng xh==*/
		}
		/*==body==*/
		.container{
			width: 1500px;
			height: auto;
		}
		
		body{
			background: #F8F2D6;
			font-family: Cambria, "Hoefler Text", "Liberation Serif", Times, "Times New Roman", "serif";
			color: #333;
		}
		#body{
			position: relative;
			align-items:center;
		}
		.h1{						/*==Link body==*/
    position: absolute;
    left: 48px;
    top: 362px;
		}
	 			.h2{
     		position: absolute;
     		left: 402px;
     		top: 362px;
	 			}
						.h3{
    				position: absolute;
    				left: 773px;
    				top: 362px;
						}
								.h4{
    						position: absolute;
    						left: 52px;
    						top: 712px;
								}
										.h5{
    								position: absolute;
    								left: 406px;
    								top: 712px;
												}
											.h6{
    									position: absolute;
    									left: 1148px;
    									top: 362px;
											}
												.h7{
    										position: absolute;
    										left: 771px;
    										top: 712px;
												}
													.h8{
    											position: absolute;
    											left: 1153px;
    											top: 712px;
													}						
		.h{
			box-shadow: 5px 10px 5px 0px gray;
		}
		.h:hover{
			box-shadow: 10px 5px 5px 0px gray;
			width: 21%;
			height: auto;							/*==Link body==*/
		}
		
		
		/*==Menu==*/
		#menu1 ul{
			list-style-type: none;
			background:linear-gradient(#17EAD9, #6078EA);
			text-align: center;
			border-radius: 0px 0px 20px 20px;		/*==menu1==*/
			box-shadow: 3px 3px 5px 0px gray;
			z-index: 1;
		}
		#menu1 ul li{
			font-variant: small-caps;
			color:#74276C;
			display: inline-table;				
			width: 120px;
			height: 40px;
			line-height: 40px;
			position: relative;
		}
		#menu1 ul li a{
			padding: 0px
			color: #000000;						
			text-decoration: none;
			display: block;
		}
		#menu1 ul li a:hover{							
			color: black;
			background:#FFFFFF;
			box-shadow: 3px 3px 3px 0px gray;					/*==menu1==*/
		}
		#menu1 ul li a>.sub-menu{									/*==menu-sub==*/
			display: none;
			position: absolute;
		}
		#menu1 ul li:hover .sub-menu{
			display: block;
			box-shadow: 5px 5px 5px 0px gray;
		}
		#menu1 .sub-menu>li:hover{
			background: #FAFAFA;
			color:#181F40;
		}
		.sub-menu{
			list-style-type: none;
			padding: 0px;									/*==menu-sub==*/
		}
		/*==Menu==*/
		/*==footer==*/
		#footer{
    position: absolute;
    top: 1048px;
    left: 14px;
    background: #D0D0D0;
    color: aliceblue;
    text-align: center;
    font-variant: small-caps;
    font-size: 14px;
    font-family: Baskerville, "Palatino Linotype", Palatino, "Century Schoolbook L", "Times New Roman", "serif";
    width: 1500px;
    height: 150px;
		}
		/*==footer==*/
	</style>
<meta charset="utf-8">
<title>CASH FASHION</title>
</head>

<body>
<div id="content" class="container">
<div id="header">
  <div class="search-box">
			<input class="search-txt" type="text" name="" placeholder="Nhập để tìm">
				<a class="search-btn" href="#">
				<img src="../pic/Untitled-1.png" width="20px">
			</a> 
	  </div>
  <a class="logo" href="#">
			<img src="../pic/logo.png"></a>
	</div>
	<div id="menu1">
	<ul>
		|<li><a href="#">Trang chủ</a></li>|
		<li><a href="#">Quần
			<ul class="sub-menu">
				<li>Fashion 1</li>
				<li>Fashion 2</li>
				<li>Fashion 3</li>
				<li>Fashion 4</li>
				<li>Fashion 5</li>
			</ul>
			</a></li>|
		<li><a href="#">Áo
			<ul class="sub-menu">
				<li>Fashion 1</li>
				<li>Fashion 2</li>
				<li>Fashion 3</li>
				<li>Fashion 4</li>
				<li>Fashion 5</li>
			</ul>
	  </a></li>|
		<li><a href="#">Giày Dép
			<ul class="sub-menu">
				<li>Fashion 1</li>
				<li>Fashion 2</li>
				<li>Fashion 3</li>
				<li>Fashion 4</li>
				<li>Fashion 5</li>
			</ul>
	  </a></li>|
		<li><a href="#">Phụ Kiện
			<ul class="sub-menu">
				<li>Fashion 1</li>
				<li>Fashion 2</li>
				<li>Fashion 3</li>
				<li>Fashion 4</li>
				<li>Fashion 5</li>
			</ul>
	  </a></li>|
		<li><a href="#">Liên hệ</a></li>|
		<li><a href="#">Góp ý</a></li>|
		<li><a href="#">Hỏi đáp</a></li>|
		</ul>
	</div>
	<div id="mxh">
	<a class="fb" href="#">
		<img class="medi" src="../pic/fb.png"
		</a>
		<a class="itg" href="#">
		<img class="medi" src="../pic/insta.png"
		</a>
			<a class="zalo" href="#">
		<img class="medi" src="../pic/zalo.png"
		</a>
	</div>
			<div id="index">
	  <a href="#"><img class="h h1" src="../pic/h1.png"></a>
	  <a href="#"><img class="h h2" src="../pic/h2.png"></a>
	  <a href="#"><img class="h h3" src="../pic/h3.png"></a>
	  <a href="#"><img class="h h4" src="../pic/h4.png"></a>
	  <a href="#"><img class="h h5" src="../pic/h5.png"></a>
	  <a href="#"><img class="h h6" src="../pic/h6.png"></a>
	  <a href="#"><img class="h h7" src="../pic/h7.png"></a>
	  <a href="#"><img class="h h8" src="../pic/h8.png"></a>
			</div>
			<div id="footer">
				<br>
				<br>
			 	@2019 CASA.COM All Right Reserved.<br>
				Mọi hình thức sao chép nội dung trên website này mà chưa được sự đồng ý đều là trái phép.<br>
				Giao diện thiết kế bởi Hữu Toàn.
				
			</div>
				
</div>
</body>
</html>
