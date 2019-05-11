<!DOCTYPE html>
<html>
	<head>

		<title>{{ page.title }}</title>
		<link rel="stylesheet" type="text/css" href="/css/main.css">
		
		<link rel="apple-touch-icon" sizes="180x180" href="/images/favicons/apple-touch-icon.png">
		<link rel="icon" type="image/png" sizes="32x32" href="/images/favicons/favicon-32x32.png">
		<link rel="icon" type="image/png" sizes="16x16" href="/images/favicons/favicon-16x16.png">
		<link rel="manifest" href="/images/favicons/site.webmanifest">

	</head>

	<body>		

		<div id="navbar">
			<nav>

				<div id="navbar_left">
					<ul>
						<li style="display:none;"><a href="#end-nav" class="skip-navigation">Skip Navigation</a></li>
						<li><a href="/"><img class="grayscale icon_left" src="/images/icons/abraham.png"></a></li>
						<li><a href="https://discord.gg/4dSYwDT"><img class="grayscale icon_left" src="/images/icons/discord.png"></a></li>
					</ul>
				</div>

				<div id="navbar_right">
					<ul>
						<li><a href="https://www.twitter.com/abraham_ai_"><img class="grayscale icon_right" src="/images/icons/twitter.png"></a></li>
						<li><a href="https://www.instagram.com/abraham_ai_"><img class="grayscale icon_right" src="/images/icons/instagram.png"></a></li>
						<li><a href="https://www.vimeo.com/abrahamai"><img class="grayscale icon_right" src="/images/icons/vimeo.png"></a></li>
						<li><a href="https://www.youtube.com/channel/UCjLCoaTyZ_EZoZgyZK2-eVQ?disable_polymer=true"><img class="grayscale icon_right" src="/images/icons/youtube.png"></a></li>
						<li><a href="https://www.github.com/abraham-ai"><img class="grayscale icon_right" src="/images/icons/github.png"></a></li>
					</ul>
				</div>

			</nav>
		</div>


		<!-- main content -->
		{{ content }}
		
		<!-- footer -->
		<footer>
			<!--
    		<ul>
        		<li><a href="https://github.com/abraham-ai">github</a></li>
			</ul>
			-->
		</footer>

	</body>

</html>