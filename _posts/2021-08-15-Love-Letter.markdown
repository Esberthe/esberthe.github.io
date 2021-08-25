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
<p> <img src="/assets/img/Love_Letter.png"> </p>
![love letter](./assets/img/Love_l.pdf){width=75%}
