<html>
	<head>
		<meta charset="UTF-8">
		<title></title>
		<style type="text/css">
			/*.box{
				margin: 0 auto;
				width: 0px;
				height: 0px;
				border-top: 50px transparent solid  ;
				border-right: 50px transparent solid ;
				border-bottom: 50px forestgreen solid ;
				border-left: 50px  transparent solid;
				
			}*/
			.fengshan{
				width: 400px;
				height: 400px;
				/*transition: all 5s ;*/
				margin: 100px auto;
				animation: shanye 0.5s linear infinite;
			}
			.fengshan div{
				display: inline-block;
				float: left;
				
			}
			.fengshan div:nth-child(1),
			.fengshan div:nth-child(4){
				border: 100px solid ;
				border-bottom-left-radius: 200px;
				border-top-right-radius: 200px;
			}
			.fengshan div:nth-child(2),
			.fengshan div:nth-child(3){
				border: 100px solid ;
				border-bottom-right-radius: 200px;
				border-top-left-radius: 200px;
			}
			/*.fengshan:hover{
				transform: rotate(10800deg) scale(2);
				
			}*/
			@keyframes shanye{
				0%{
					transform: rotate(0deg) ;
				}
				25%{
					transform:  rotate(120deg) ;
				}
				50%{
					transform:  rotate(240deg) ;
				}
				75%{
					transform:  rotate(360deg);
				}
				100%{
					transform:  rotate(0deg);
				}
			}
		</style>
	</head>
	<body>
		<!--<div class="box"></div>-->
		<div class="fengshan">
			<div></div>
			<div></div>
			<div></div>
			<div></div>
		</div>
	</body>
</html>
