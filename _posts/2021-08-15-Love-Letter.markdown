---
layout: post
title:  "Love Letter "
date:   2021-08-15 15:37:16 -0400
categories: jekyll update
---
<html>

<head>
	<script src=
"https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js">
	</script>
	<style>
		#geek {
			padding: 65px 0;
		}
	</style>

	<script>
		$(document).ready(function() {
			$(document).keydown(function(event) {

				// 86 is the keycode of v
				if (event.ctrlKey == true && (event.which == '86')) {
					$("#d2").text('paste. not allowed!');
					event.preventDefault();
				}

				// 88 is the keycode of x
				if (event.ctrlKey == true && (event.which == '88')) {
					$("#d2").text('cut. not allowed!');
					event.preventDefault();
				}

				// 67 is the keycode of c
				if (event.ctrlKey == true && (event.which == '67')) {
					$("#d2").text('copy. not allowed!');
					event.preventDefault();
				}

				// Above all three can be combined into one, above is
				// executed separately for understanding purposes.
				/* if (event.ctrlKey==true && (event.which == '86'
				|| event.which == '67' || event.which == '88')) {
					alert('cut. copy. paste. not allowed!');
					event.preventDefault();
				} */
			});
			$('textarea').mousedown(function(e) {
				if (e.button == 2) {
					alert('right-click is disabled!');
					e.preventDefault();
				}
			});
		});
	</script>
</head>

<body>
	<center>
			
			
			<p id="d2" style="color:red"></p>

	</center>
</body>
	<img src="/assets/img/Love_Letter .png"/>
<p> <img src="https://export-download.canva.com/Ts_II/DAEnaOTs_II/53/6566223125.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAJHKNGJLC2J7OGJ6Q%2F20210824%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20210824T234217Z&X-Amz-Expires=11765&X-Amz-Signature=08720e36c52fcdca4e944b9260c48aa7fce75b26c91b2b9e7f9e319bba56a928&X-Amz-SignedHeaders=host&response-content-disposition=attachment%3B%20filename%2A%3DUTF-8%27%27Love_Letter%2520.gif&response-expires=Wed%2C%2025%20Aug%202021%2002%3A58%3A22%20GMT"/>
<img src="https://www.canva.com/design/DAEnaOTs_II/0nvW4kDJqxhjYzOoHJXMqA/view?utm_content=DAEnaOTs_II&utm_campaign=designshare&utm_medium=link&utm_source=homepage_design_menu"/>
