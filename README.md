<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<title>分析图</title>
	<style type="text/css">
  	body{
		background:-webkit-radial-gradient(circle,#334750,#020205) 
	}
	*{
		margin: 0;
		padding: 0;
	}
	.box{
		width:600px;
		height:150px;
		color: white;
		margin:0 auto;
		text-align: center;
	}
	h1{
		word-spacing: 10px;
		margin: 15px;
	}
	#second{
		letter-spacing: 6px;
		margin: 15px;
	}
	#third{
		font: 20px fantasy;
		margin: 15px;
	}
	.body{
		width: 500px;
		height: auto;
		margin:0 auto;
	}
	.one,.two,.three,.four,.five{
		width: 50px;
		height: 100px;
		border-top-left-radius: 15px 50px;
		border-top-right-radius: 15px 50px;
		border-bottom-left-radius: 15px 50px;
		border-bottom-right-radius: 15px 50px;
		background-color: #9CAEB3;
		cursor: pointer;
		transition-duration: 1s;
		transition-property: all;
		transition-delay:0s;
		transition-timing-function: initial;
		position: relative;
	}
	.one:after,.two:after,.three:after,.four:after,.five:after{
		content: " ";
		position: absolute;
		border-top:50px solid #BDCBCE;
		border-right:15px solid #BDCBCE;
		border-bottom:50px solid #BDCBCE;
		border-left:15px solid #BDCBCE;
		border-top-left-radius: 15px 50px;
		border-top-right-radius: 15px 50px;
		border-bottom-left-radius: 15px 50px;
		border-bottom-right-radius: 15px 50px;
		transition-duration: 1s;
		transition-property: all;
		transition-delay:0s;
		transition-timing-function: initial;
		left: 20px;
	}
	.one:hover{
		width: 300px;
		background-color: #940030;
	}
	.one:hover::after{
		left: 270px;
		border-top:50px solid #C20039;
		border-right:15px solid #C20039;
		border-bottom:50px solid #C20039;
		border-left:15px solid #C20039;v
	}
	.one:before{
		content: "phone";
		color: white;
		position: absolute;
		top: 40px;
		left: 600px;

	}
	.two:hover{
		width: 300px;
		background-color: #940030;
	}
	.two:hover::after{
		left: 270px;
		border-top:50px solid #C20039;
		border-right:15px solid #C20039;
		border-bottom:50px solid #C20039;
		border-left:15px solid #C20039;v
	}
	.two:before{
		content: "lapdesk";
		color: white;
		position: absolute;
		top: 40px;
		left: 600px;

	}
	.three:hover{
		width: 300px;
		background-color: #940030;
	}
	.three:hover::after{
		left: 270px;
		border-top:50px solid #C20039;
		border-right:15px solid #C20039;
		border-bottom:50px solid #C20039;
		border-left:15px solid #C20039;v
	}
	.three:before{
		content: "topdesk";
		color: white;
		position: absolute;
		top: 40px;
		left: 600px;

	}
	.four:hover{
		width: 300px;
		background-color: #940030;
	}
	.four:hover::after{
		left: 270px;
		border-top:50px solid #C20039;
		border-right:15px solid #C20039;
		border-bottom:50px solid #C20039;
		border-left:15px solid #C20039;v
	}
	.four:before{
		content: "mouse";
		color: white;
		position: absolute;
		top: 40px;
		left: 600px;

	}
	.five:hover{
		width: 300px;
		background-color: #940030;
	}
	.five:hover::after{
		left: 270px;
		border-top:50px solid #C20039;
		border-right:15px solid #C20039;
		border-bottom:50px solid #C20039;
		border-left:15px solid #C20039;v
	}
	.five:before{
		content: "keyword";
		color: white;
		position: absolute;
		top: 40px;
		left: 600px;
	}
  </style>
</head>
<body>
	<div class="box">
		<h1>Wicked CSS3 3d bar chart</h1>
		<p id="second">NOW WITH ANIMATION</p>
		<p id="third">wdguohl.guthub\wdguol-css</p>
	</div>
	<div class="body">
		<div class="one">
			
		</div>
		<div class="two">
			
		</div>
		<div class="three">
			
		</div>
		<div class="four">
			
		</div>
		<div class="five">
			
		</div>
	</div>
</body>
</html>
