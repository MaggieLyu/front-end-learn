<!doctype html>
<html>
	<head>
	<title>水平测试</title>
	<meta charset="UTF-8"> 
  <!----------
  <link rel="stylesheet" type="text/css" href="common.css" />
	<link rel="stylesheet" type="text/css" href="test.css" />
  --------->
  <style>
  body{
	margin:0px;
	padding:0px;
	font-size:12px;
	font-family:"Î¢ÈíÑÅºÚ",arial;
	background:#dedede;
}
.lt{
	float:left;
}
.rt{
	float:right;
}
.clear{
	clear:both;
}
  header{
	width:1282px;
	height:60px;
	margin:0px auto;
	background-color:#333;	
}
header div{
	width:1240px;
	overflow:hidden;
	margin:0px auto;
	padding-left:17px;
}
header div ul li{
	Float:left;
	line-height:60px;
	text-align:center;
	list-style:none;
}
header div ul li b{
	display:inline-block;
	width:6px;
	height:6px;
	background:#000;
	border-radius:50%;
	margin:0px 5px;
}
header div ul li a{
	display:inline-block;
	width:70px;
	height:60px;
	color:#fff;
	font-size:12px;
	font-weight:500;
	text-decoration:none;
}
header div ul li a:hover{
	color:#9bafa3;
}
/******正文部分 width=“1238px” border="1px solid #cdcdcd"*****/
section{
	width:1240px;
	margin:0px auto;
}
section>div{
	width:1238px;
	margin:20px 0px;
	background:#fff;
	border:1px solid #cdcdcd;
	box-shadow:1px 0px 2px #9f9f9f;
	padding:10px 0px;
}
/**************文章1 article1************/
#article1 h2,#article2 h2,#article3 h2,#article4 h2,#userinfor h2{
	color:#626262;
}
#article1 h3,#article2 h3,#article3 h3,#article4 h3,#userinfor h3 {
	color:#717171;
	font-weight:400;
}
#article1  h3 a,#article2  h3 a,#article3 h3 a,#article4  h3 a{
	text-decoration:none;
	color:#717171;
	margin-right:5px;
}
/**************文章2 article2************/
div#article2 ul{
	padding-left:20px;
}
div#article2 ul li{
	list-style:none;
	width:150px;
	height:25px;
	line-height:25px;
}
/**************文章3 图片层************/
div#article3 div{
	width:570px;
	padding:10px;
	border:1px solid #cecece;
	margin-top:15px;
}
div#article3 div p{
	text-align:center;
}
/**************文章4 列表和表格************/
ol li{
	height:25px;
	width:100px;
}
#article4 table{
	width:1200px;
	border:none;
}
#article4 table thead{
	background:#333;
	color:#fff;
	font-weight:bold;
}
#article4 table tr td{
	padding:5px;
	width:390px;
	height:25px;
}
#article4 table tfoot{
	background:#ccc;
	color:#000;
	font-weight:bold;
}
/**************用户注册信息************/
div#userinfor h1{
	display:block;
	border-left:3px solid #cacaca;
	padding-left:10px;
	height:45px;
	line-height:45px;
}
div#userinfor table{
	margin-left:270px;
}
div#userinfor table tr td{
	
}
div#userinfor form input.sex{
	background:#3e99ff;
	color:#fff;
}
div#userinfor form p{
	color:#a4999d;
}
div#userinfor form input.submit{
	width:1180px;
	height:40px;
	background:#3355d0;
	color:#fff;
	font-size:16px;
	font-weight:bold;
	border:none;
	border-radius:8px;
	margin:10px auto;
}
/*****************************页尾部分************************************/
footer{
	margin:0px auto;
	background:#000;
	width:1280px;
	height:70px;
	padding-top:20px;
}
footer p{
	text-align:center;
	color:#fff;
}
  </style>
	</head>
	<body>
		<!-------------页面头部----------------->
		<header>
			<div>
				<a href="www.baidu.com"><img src="images/baidulogo.png"/></a>
				<ul class="rt">
					<li><b></b><a href="#link1">导航链接一</a></li>
					<li><b></b><a href="#link2">导航链接二</a></li>
					<li><b></b><a href="#link3">导航链接三</a></li>
					<li><b></b><a href="#link4">导航链接四</a></li>
				</ul>
			</div>
		</header>
		<!------------------正文部分------------------->
		<section>
		<!---------------------文章一-------------------->
			<div id="article1">
				<blockquote>
					<h1><a name="link1">什么是github?</a></h1>
					<h2>文章二级标题</h2>
					<h3><a href="#">文章作者</a><time datetime="2017-3-12">2017-3-12</time></h3>
					<p>&nbsp;&nbsp;GitHub是一个分布式的版本控制系统，最初由Linus Torvalds编写，用作Linux内核代码的管理。在推出后，Git在其它项目中也取得了很大成功，尤其是在Ruby社区中。目前，包括Rubinius、Merb和Bitcoin在内的很多知名项目都使用了Git。Git同样可以被诸如Capistrano和Vlad the Deployer这样的部署工具所使用。</p>
					<p>GitHub是一个分布式的版本控制系统，最初由Linus Torvalds编写，用作Linux内核代码的管理。<br>在推出后，Git在其它项目中也取得了很大成功，尤其是在<a href="http://ife.baidu.com">Ruby社区</a>中。目前，包括<b>Rubinius、Merb和Bitcoin</b>在内的很多知名项目都使用了Git。Git同样可以被诸如Capistrano和Vlad the Deployer这样的部署工具所使用。</p>
					<img src="images/github.jpg"/>
					<p>&nbsp;&nbsp;GitHub是一个分布式的版本控制系统，最初由Linus Torvalds编写，用作Linux内核代码的管理。在推出后，Git在其它项目中也取得了很大成功，尤其是在Ruby社区中。</p>
					<p>GitHub是一个分布式的版本控制系统，最初由<b>Linus Torvalds</b>编写，用作Linux内核代码的管理。目前，包括<a href="#">Rubinius、Merb和Bitcoin</a>在内的很多知名项目都使用了Git。Git同样可以被诸如Capistrano和Vlad the Deployer这样的部署工具所使用。</p>
				</blockquote>
			</div>
			<!---------------------文章二-------------------->
			<div id="article2">
				<blockquote>
					<h1><a name="link2">另一篇文章一级标题</a></h1>
					<h2>文章二级标题</h2>
					<h3><a href="#">文章作者</a><time datetime="2017-3-12">2017-3-12</time></h3>
					<p>&nbsp;&nbsp;GitHub是一个分布式的版本控制系统，最初由Linus Torvalds编写，用作Linux内核代码的管理。在推出后，Git在其它项目中也取得了很大成功，尤其是在Ruby社区中。目前，包括Rubinius、Merb和Bitcoin在内的很多知名项目都使用了Git。</p>
					<p>GitHub是一个分布式的版本控制系统，最初由Linus Torvalds编写，用作Linux内核代码的管理。<br>在推出后，Git在其它项目中也取得了很大成功，尤其是在<a href="http://ife.baidu.com">Ruby社区</a>中。目前，包括<b>Rubinius、Merb和Bitcoin</b>在内的很多知名项目都使用了Git。Git同样可以被诸如Capistrano和Vlad the Deployer这样的部署工具所使用。</p>
					<img src="images/github.jpg"/>
					<ul>
						<li>列表项目一</li>
						<li>列表项目二</li>
						<li>列表项目三</li>
					</ul>
				</blockquote>
			</div>
					<!---------------------文章三 图片层-------------------->
			<div id="article3">
				<blockquote>
					<h1><a name="link3">图片</a></h1>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
					<div>
						<p>好看的图片</p>
						<img src="images/github.jpg">
					</div>
				</blockquote>
			</div>
			<!---------------------文章四-------------------->
			<div id="article4">
				<blockquote>
					<h1><a name="link4">最后一篇文章一级标题</a></h1>
					<h2>文章二级标题</h2>
					<h3><a href="#">文章作者</a><time datetime="2017-3-12">2017-3-12</time></h3>
					<ol type="1" start="1">
						<li>排名1</li>
						<li>排名2</li>
						<li>排名3</li>
					</ol>
					<table cellpadding="0px" cellspacing="0px">
						<thead>
							<tr>
								<td>表头</td>
								<td>表头</td>
								<td>表头</td>
							</tr>
						</thead>
						<tbody>
							<tr>
								<td>表内单元格</td>
								<td>表内单元格</td>
								<td><a href="#">操作</a></td>
							</tr>
							<tr>
								<td>表内单元格</td>
								<td>表内单元格</td>
								<td><a href="#">操作</a></td>
							</tr>
							<tr>
								<td>表内单元格</td>
								<td>表内单元格</td>
								<td><a href="#">操作</a></td>
							</tr>
							<tr>
								<td>表内单元格</td>
								<td>表内单元格</td>
								<td><a href="#">操作</a></td>
							</tr>
						</tbody>
						<tfoot>
							<tr>
								<td>总计</td>
								<td colspan="2">1000</td>
							</tr>
						</tfoot>
					</table>
				</blockquote>
			</div>
			<div id="userinfor">
				<blockquote>
					<h1><a name="link4">用户注册信息</a></h1>
					<form>
						<table>
							<tr>
								<td>请输入邮箱地址</td>
								<td>
									<input type="email" value="这是一个文本输入框">
								</td>
							</tr>
							<tr>
								<td></td>
								<td>
									<p>邮箱地址请按要求格式输入</p>
								</td>
							</tr>
							<tr>
								<td>请输入密码</td>
								<td>
									<input type="password" value="12345678">
								</td>
							</tr>
							<tr>
								<td>请重新输入密码</td>
								<td>
									<input type="password" value="12345678">
								</td>
							</tr>
							<tr>
								<td></td>
								<td>
									<p>密码请为6-16位英文数字</p>
								</td>
							</tr>
							<tr>
								<td>性别</td>
								<td>
									<input class="sex" name="sex" type="radio" value="male" id="male" checked><label for="male">男</label>
									<input class="sex" name="sex" type="radio" value="female" id="female" /><label for="female">女</label>
								</td>
							</tr>
							<tr>
								<td>城市</td>
								<td>
									<select name="city" size="1">
										<option value="北京" >北京</option>
										<option value="北京" selected>苏州</option>
										<option value="北京" >上海</option>
									</select>
								</td>
							</tr>
							<tr>
								<td>爱好</td>
								<td>
									<input type="checkbox" name="hobby" value="exercise" id="exercise" ><label for="exercise">运动</label>
									<input type="checkbox" name="hobby" value="art" id="art" ><label for="art">艺术</label>
									<input type="checkbox" name="hobby" value="science" id="science" ><label for="science">科学</label>
								</td>
							</tr>
							<tr>
								<td>个人描述</td>
								<td>
									<textarea name="userinfor" cols="80" rows="5">这是一个多行输入框，输入您的个人描述</textarea>
								</td>
							</tr>
						</table>
						<input type="submit" value="确认提交" class="submit">
					</form>
				</blockquote>
			</div>
		</section>
		<!-------------------页尾部分------------------>
		<footer>
		<p>版权所有&copy;</p>
		</footer>
	</body>
</html>
