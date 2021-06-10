
<!DOCTYPE HTML>
<html>
	<head>
		<title>GitHub Proxy 代理加速</title>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1, user-scalable=no" />
		<link rel="stylesheet" href="https://cdn.ioiox.com/website/ghproxy.com/assets/css/main.min.css" />
		<link rel="shortcut icon" href="https://cdn.ioiox.com/website/ghproxy.com/favicon.ico">

		<!-- Twitter Cards -->
		<meta name="twitter:card" content="summary_large_image" />
		<meta name="twitter:site" content="@stilleshan" />
		<meta name="twitter:creator" content="@stilleshan" />
		<meta property="og:url" content="https://ghproxy.com" />
		<meta property="og:title" content="GitHub Proxy 代理加速" />
		<meta property="og:description" content="GitHub 文件 , Releases , archive 以及 raw.githubusercontent.com 文件加速下载服务." />
		<meta property="og:image" content="https://cdn.ioiox.com/website/ghproxy.com/images/ghproxy_com_twitter_800.jpg" />

		<script data-ad-client="ca-pub-3183896578736075" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>

		<!-- Global site tag (gtag.js) - Google Analytics -->
		<script>
			window.ga_tid = "UA-184918992-1";
			window.ga_url = "https://ga.ioiox.com";
			123
		</script>
		<script src="https://cdn.ioiox.com/github/giuem/ga-proxy/ga.min.js" async></script>
	</head>

	<body class="landing is-preload">
		<div id="page-wrapper">

			<!-- Header -->
				<header id="header" class="alt">
					<h1><a href="https://ghproxy.com">GitHub Proxy</a></h1>
					<nav id="nav">
						<ul>
							<li><a href="https://ghproxy.com">首页</a></li>
							<li><a href="https://freefrp.net" target="_blank">免费 FRP 内网穿透</a></li>
							<li><a href="https://rssforever.com" target="_blank">RSS 服务</a></li>
							<li><a href="https://www.ioiox.com" target="_blank">博客</a></li>
						</ul>
					</nav>
				</header>


			<!-- CTA -->
				<section id="cta">
					<img src="https://cdn.ioiox.com/website/ghproxy.com/images/github.png" height="100" width="100">
					<br />
					<h2>GitHub Proxy</h2>
					<p>GitHub 文件 , Releases , archive 以及 raw.githubusercontent.com 文件加速下载服务.</p>

					<form action="./" method="get" target="__blank">
						<div class="row gtr-50 gtr-uniform">
							<div class="col-8 col-12-mobilep">
								<input class="block url" type="text" name="q" id="email" placeholder="输入 GitHub 文件链接"
								pattern="^((https|http):\/\/)?(github\.com\/.+?\/.+?\/(?:releases|archive|blob)|(raw\.githubusercontent\.com))\/.+$" required>
							</div>
							<div class="col-4 col-12-mobilep">
								<input type="submit" value="下载">
							</div>
						</div>
					</form>

				</section>


				<section id="main" class="container">
					<header>
						<h2>使用说明</h2>
						<p>本站视网络情况选择最优的线路以提高下载体验
							<br>
							当前服务器线路&nbsp; ：韩国 CN2 GIA</p>
					</header>
					<div class="row">
						<div class="col-12">

							<!-- Text -->
								<section class="box">
									<h3>终端命令行</h3>
									<p>支持终端命令行下载 , 例如 git clone , wget , curl 等以及 <font color="red">raw.githubusercontent.com</font> 文件下载.
									<br>
									<b>注意：</b>不支持 SSH Key 方式 git clone 下载.</p>

									<hr />

									<header>
										<h4><b>git clone</b></h4>
									</header>
									<p><b>git clone</b> <font color="red">https://ghproxy.com/</font><font color="green">https://github.com/stilleshan/ServerStatus.git</font></p>
									
									<header>
										<h4><b>wget & curl</b></h4>
									</header>
									<p><b>wget</b> <font color="red">https://ghproxy.com/</font><font color="green">https://github.com/stilleshan/ServerStatus/archive/master.zip</font>
									<br>
									<b>wget</b> <font color="red">https://ghproxy.com/</font><font color="green">https://raw.githubusercontent.com/stilleshan/ServerStatus/master/Dockerfile</font>
									<br>
									<b>curl -O</b> <font color="red">https://ghproxy.com/</font><font color="green">https://github.com/stilleshan/ServerStatus/archive/master.zip</font>
									<br>
									<b>curl -O</b> <font color="red">https://ghproxy.com/</font><font color="green">https://raw.githubusercontent.com/stilleshan/ServerStatus/master/Dockerfile</font></p>								
								</section>

								<section class="box">
									<h3>首页下载</h3>
									<p>在本页地址栏输入合规链接（参考以下链接）点击下载按钮
									<br>
									本站已支持 <font color="red">raw.githubusercontent.com</font> 链接下载</p>

									<hr />

									<header>
										<h4><b>Raw 文件</b></h4>
									</header>
									<p>https://raw.githubusercontent.com/stilleshan/ServerStatus/master/Dockerfile</p>

									<header>
										<h4><b>分支源码</b></h4>
									</header>
									<p>https://github.com/stilleshan/ServerStatus/archive/master.zip</p>									
									
									<header>
										<h4><b>Releases 源码</b></h4>
									</header>
									<p>https://github.com/stilleshan/ServerStatus/archive/v1.0.tar.gz</p>


									<header>
										<h4><b>Releases 文件</b></h4>
									</header>
									<p>https://github.com/fatedier/frp/releases/download/v0.33.0/frp_0.33.0_linux_amd64.tar.gz</p>										
								</section>
						</div>
					</div>	
				</section>			
							

			<!-- Footer -->
				<footer id="footer">
					<ul class="copyright">
						<li>&copy; ghproxy.com. All rights reserved.</li><li>Github Project : <a href="https://github.com/hunshcn/gh-proxy" target="_blank">hunshcn/gh-proxy</a></li>
					</ul>
				</footer>

		</div>

		<!-- Scripts -->
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/jquery.min.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/jquery.dropotron.min.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/jquery.scrollex.min.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/browser.min.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/breakpoints.min.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/util.js"></script>
			<script src="https://cdn.ioiox.com/website/ghproxy.com/assets/js/main.js"></script>
	</body>
</html>