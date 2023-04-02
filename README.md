<!DOCTYPE html>
<html>
<head>
	<title>Github Hareketli Efekt</title>
	<style>
		@keyframes rotate {
			0% {
				transform: rotate(0deg);
			}
			100% {
				transform: rotate(360deg);
			}
		}

		.github-logo {
			animation: rotate 2s linear infinite;
		}
	</style>
</head>
<body>
	<a href="https://github.com" target="_blank">
		<img class="github-logo" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Github Logo" width="50">
	</a>
</body>
</html>
