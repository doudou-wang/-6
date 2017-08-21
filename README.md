	<!DOCTYPE html>
	<html>
	<head>
		<meta charset="utf-8">
		<meta http-equiv="X-UA-Compatible" content="IE=edge">
		<title>报纸排版</title>
		<link rel="stylesheet" href="">
		<style type="text/css" media="screen">
			*{
				padding:0;
				margin:0;
			}

			#wrap{
				width: 980px;
				height: 1386px;
				margin:0 auto;
			}
     		/*头部开始*/
			#header{
				width: 892px;
				height: 61px;
				border-bottom: 2px solid #928e8f;
				margin:0 auto;
				/*padding: 1px;*/
			}

			#header p{
				color: #d45d5c;
				font-size: 12px;
				font-family: "黑体";
				float: right;
				margin-top: 46px;
			}

			#header #box_01{
				width: 110px;
				height: 61px;
				background-color: #d45d5c;
				overflow: hidden;
			}

			#header #box_01 div{
				color: #fff;
				font-size: 12px;
				font-family: "黑体";
				margin-top: 46px;
				margin-left: 5px;
			}
			/*头部结束*/

			/*主体部分开始*/
			#mainbody{
				width: 892px;
				margin: 0 auto;
			}

			/*左上方大图*/
			#mainbody #box_01{
				margin-top: 35px;
				width: 641px;
				height: 301px;
				background-image: url(imgs/CSS019_01.png);
				overflow: hidden;
				float: left;
			}

			/*大图中的绿色框*/
			#mainbody #box_02{
				width: 191px;
				height: 301px;
				background-color: #345542;
				opacity: 0.7;
				margin-top: 2px;
				float: left;
				/*因切图没切好做的调整*/
			}

			/*大图中的粉色框*/
			#mainbody #box_03{
				width: 191px;
				height: 301px;
				background-color: #bb7b79;
				opacity: 0.5;
				float: right;
				margin-top: 2px;
			}

			/*右上的6种文字*/
			#mainbody #box_04{
				width: 203px;
				height: 299px;
				border-top: 2px solid #cc8091;
				float: right;
				margin-top: 37px;
			}

			/*第一种字体*/
			#mainbody #box_04 #p_01{
				font-size: 24px;
				color: #000;
				font-family: "微软雅黑";
				text-decoration: underline;
				/*小型大写字母*/
				font-variant:small-caps;
			}

			/*第二种字体*/
			#mainbody #box_04 #p_02{
				font-size: 12px;
				color: #676767;
				font-family: "楷体";
			}

			/*第三种字体*/
			#mainbody #box_04 #p_03{
				font-size: 116px;
				color: #75b86b;
				font-family: "微软雅黑";
				font-style: italic;
			    margin-left: -16px;
			}

			/*第四种字体*/
			#mainbody #box_04 #p_04{
				font-size: 55px;
				color: #cc8091;
				font-family: "微软雅黑";
				float: left;
				margin-top: -4px;
			}

			/*第五种字体和第六种字体的盒子*/
			#mainbody #box_04 #box_05{
				float: right;
				margin-right: 31px;
    			margin-top: 15px;
			}

			/*第五种字体*/
			#mainbody #box_04 #box_05 #p_05{
				font-size: 21px;
				color: #cc8091;
				font-family: "微软雅黑";
			}

			/*第六种字体*/
			#mainbody #box_04 #box_05 #p_06{
			    font-size: 12px;
				color: #cc8091;
				font-family: "微软雅黑";
			}

			/*中间三段文字*/
			/*第一段文字*/
			#mainbody #box_06{
				width: 228px;
				height: 167px;
				margin-top: 42px;
				float: left;
			}

			/*第一段文字标题*/
			#mainbody #box_06 h3{
				font-size: 16px;
				color: #418c59;
				text-decoration: underline;
				font-family: "微软雅黑";
				line-height: 32px;
			}

			/*第一段文字文字*/
			#mainbody #box_06 p{
				font-size: 12px;
				color: #767777;
				line-height: 16px;
				font-family: "宋体";
			}

			/*第二段文字*/
			#mainbody #box_07{
				width: 205px;
				height: 167px;
				margin-top: 42px;
				margin-left: 27px;
				float: left;
			}

			/*第二段文字标题*/
			#mainbody #box_07 h3{
				font-size: 16px;
				color: #d2994f;
				text-decoration: underline;
				font-family: "微软雅黑";
				line-height: 32px;
			}

			/*第二段文字文字*/
			#mainbody #box_07 p{
				font-size: 12px;
				color: #231815;
				line-height: 16px;
				font-family: "微软雅黑";
				opacity: 0.7;
			}

			/*第三段文字*/
			#mainbody #box_08{
				width: 132px;
				height: 167px;
				margin-top: 42px;
				margin-left: 27px;
				float: left;
			}

			/*第三段文字标题*/
			#mainbody #box_08 h3{
				font-size: 16px;
				color: #cc7680;
				text-decoration: underline;
				font-family: "微软雅黑";
				line-height: 32px;
			}

			/*第三段文字文字*/
			#mainbody #box_08 p{
				font-size: 12px;
				color: #231815;
				line-height: 19px;
				font-family: "微软雅黑";
				opacity: 0.7;
			}

			#mainbody #box_08 p span{
				color: #cd4a48;
				font-style: italic;
			}

			/*中间的标题*/
			#mainbody #box_09{
				width: 415px;
				height: 151px;
				border-bottom: 2px solid #11456b;
				float: left;
				margin-top: 75px;
				overflow: hidden;
			}

			#mainbody #box_09 h2 span{
				font-size: 72px;
				color: #f5e327;
				font-family: "黑体";
				font-style: italic;
				line-height: 50px;
				padding-right: 23px;
			}

			#mainbody #box_09 h2{
				font-size: 42px;
				color: #11456b;
				font-family: "黑体";
				line-height: 40px;
			}

			/*p：前端技术领域*/
			#mainbody #box_09 p{
				font-size: 33px;
				color: #11456b;
				font-family: "黑体";
				line-height: 45px;
			}

			/*中间图片*/
			#mainbody #box_10 {
				width: 458px;
				height: 257px;
				float: right;
				margin-top: 75px;
			}

			/*左下角文字*/
			#mainbody #box_11{
				width: 406px;
				height: 427px;
				float: left;
				margin-top: 25px;
				position: relative;
			}

			#mainbody #box_11 p{
				font:12px "宋体";
				color: #767777;
				text-indent: 2em;
			}

			/*使用伪类时不能有兄弟节点*/
			#mainbody #box_11 p:first-child{
				text-indent: 0em;
			}

			/*首个文字*/
			#box_11 p:first-child::first-letter{
				font-size: 70px;
				color: #f5e327;
				font-family: "微软雅黑";
				float: left;
				margin-top: -12px;
			}

			/*下方图片*/
			#mainbody  img{
				width: 192px;
				height: 320px;
				float: right;
				margin-left: 20px;
				margin-bottom: 10px;
				margin-top: 20px;
			}

			/*右下角框*/
			#mainbody #box_13{
				width: 459px;
				height: 318px;
				float: right;
				margin-top: 28px;
				background-color: #eeeed6;
			}

			/*右下角框列表*/
			#mainbody #box_13 ul{
				list-style-image: url(imgs/CSS019_04.png); 
				list-style-position: inside;
				margin-top: 30px;
				margin-left: 30px;
			}
			
			/*右下角框列表文字*/
			#mainbody #box_13 ul li{
				font: 16px/36px "宋体";
				color: #5a5b5b;
				text-align: left;
			}

			/*右下角框列表点点后文字*/
			#mainbody #box_13 ul li span{
				font: 12px/20px "宋体";
				color: #5a5b5b;
				text-align: right;
				font-style: italic;
			}

			/*右下角红色小框*/
			#mainbody #box_14{
				width: 260px;
				height: 160px;
				float: left; 
				margin-top: 20px;
				background-color: #d55d5c;
			}

			/*右下角红色小框中的0*/
			#mainbody #box_14 #box_15{
				float: left;
				width: 78px;
				height: 86px;
				color: #fff;
				font-size: 110px;
				line-height: 82px;
				text-align: center;
				font-family: "微软雅黑";
				border-right: 2px solid #fff;
				margin-top: 40px;
			}

			/*右下角红色小框右边文字*/
			#mainbody #box_14 #box_16 {
				float: left;
				margin-top: 45px;
				margin-left: 10px;
			}

			#mainbody #box_14 #box_16 #p_01{
				font:21px/24px "黑体";
				color: #fff;
				font-style: italic;
			}

			#mainbody #box_14 #box_16 #p_02{
				font:12px/18px "黑体";
				color: #fff;
			}

			/*右下角hello world*/
			#mainbody #box_13 #box_17{
				float: left;

				width: 162px;
				margin-top: 20px;
				margin-left: 10px;
				font:14px/16px "黑体";
				font-style: italic;
				color: #5a5b5b;
			}

			/*右下角红色引号*/
			#mainbody #box_13 p #span_01{
				float: left;
				font:72px/16px "黑体";
				margin: 16px 0px -16px -39px;
				color: #d45d5c;
			}

			#mainbody #box_13 p #span_02{
				float: right;
				font:72px/16px "黑体";
				color: #d45d5c;
				margin-right: -39px;
				margin-top: 32px;
			}
			/*主体部分结束*/

			/*footer部分开始*/
			#footer{
				float: left;
				width: 892px;
				height: 61px;
				border-top: 1px solid #928e8c;
				/*clear: both;*/
				margin-top: 40px;
				margin-left: 44px;
				/*overflow: hidden;*/
				/*padding: 1px;*/
			}

			#footer p{
				color: #d45d5c;
				font-size: 12px;
				font-family: "黑体";
				float: right;
			}
		</style>
	</head>
	<body>
		<div id="wrap">
			<div id="header">
			<p>2016.3</p>
				<div id="box_01">
					<div>ife.baidu.com</div>
				</div>	
			</div>
			<div id="mainbody">
				<div id="box_01">
					<div id="box_02"></div>
					<div id="box_03"></div>
				</div>
				<div id="box_04">
					<p id="p_01">About<br />Technologe</p>
					<p id="p_02">About technologe about technologe <br />about technologe</p>
					<p id="p_03">700</p>
					<p id="p_04">3.2</p>
					<div id="box_05">
						<p id="p_05">CSS</p>
						<p id="p_06">CSSCSSCSSCSS</p>
					</div>
				</div>
				<div id="box_06">
					<h3>What</h3>
					<p>前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端
					端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端
					端前端前端前端前端前端前端</p>
				</div>
				<div id="box_07">
					<h3>When</h3>
					<p>前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前</p>
				</div>
				<div id="box_08">
					<h3>How</h3>
					<p>前端前端前端前端<br /> 前端前端前端前端前端 <br />端前端前端前端</p>
					<br />
					<p>What------- <span>40%</span><br />
					What------- <span>30%</span><br />
					What------- <span>30%</span>
					</p>
				</div>
				<div id="box_09">
					<h2><span>THE</span>TECHNOLOGE <br />OF FRONT </h2>
					<p>前端技术领域</p>
				</div>
				<div id="box_10">
					<img src="imgs/CSS019_02.png" alt="CSS019_02">
				</div>
				<div id="box_11">
					<p>前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端
					<!-- <div id="box_12"> -->
						<img src="imgs/CSS019_03.png" alt="CSS019_03">
					<!-- </div> -->
					端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
					<p>前端前端前端前端前端前端前端前端前端前端前端前端端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端</p>
					<p>前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端前端
					</p>
				</div>
				<div id="box_13">
					<ul>
						<li>端前端前端前端前端前端......................<span>前端</span></li>
						<li>前端前端前端前端...........................<span>前端前</span></li>
						<li>端前端前端前端前端前端前端..................<span>前端</span></li>
					</ul>
					<div id="box_14">
						<div id="box_15">0</div>
						<div id="box_16">
							<p id="p_01">ONE TWO <br />THREE FORE FIVE</p>
							<p id="p_02">hello world hello world<br /> hello world</p>
						</div>
					</div>
					<div id="box_17">
						<p><span id="span_01">“</span>hello world hello world hello world hello world hello world hello world hello world hello world hello world hello world<span id="span_02">”</span></p>
					</div>
					
				</div>
			</div>
			<div id="footer">
				<p>ife.baidu.com</p>
			</div>
		</div>
	</body>
	</html>
