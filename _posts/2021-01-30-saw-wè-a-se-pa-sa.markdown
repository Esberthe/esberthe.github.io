---
layout: post
title:  "Je w pa bon"
date:   2021-01-30 15:37:16 -0400
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
			<p id="d1" style="font-weight:bolder">
				The below text area won't allow any cut, copy,
				paste and right-click operations.
			</p>
			<p id="d2" style="color:red"></p>

	</center>
</body>
<p> <img src="/assets/img/saw-wè.jpg"/> </p>

<p>Pa bat kòw <br>
Pa kraze tèt ou <br>
Pa panse mwen se yon enbesil <br>
Si w ta wè ou fè m mal <br>
Epi m vire lòt bò machwè m ba ou <br></p>

<p>Si w wè w ta vle fese m atè<br>
Epi m ap souri ba ou <br>
Pa pran m pou entatad <br>
Se may mwen sa <br></p>

<p>Si w wè ou ta vle tire m <br>
M lonje zam nan ba ou <br>
Pa panse m se yon egare<br>
Se fent mwen sa <br></p>

<p>M ap vann ou, m ap achte w <br>
San w pa rann ou kont ou te chanje mèt <br>
Wi, m piti men m pa pitimi <br>
Wi, m gen ti figi lèzanj ki paka kase ze <br>
Men pa fye sa je w ba ou <br>
Paske je w p ap janm bon <br>
Si se mwen ou vle konprann <br></p>
