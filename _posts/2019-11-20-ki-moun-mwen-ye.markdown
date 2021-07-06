---
layout: post
title:   "Kiyès mwen ye?"
date:   2019-11-20 15:37:16 -0400
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


<p>
Mwen pa moun janti sa <br>
Ou vle ki di w wi <br>
Chak lè w anvi yon bagay nan men l <br>
Mwen pa moun kapon sa <br>
K ap kache w verite <br>
Pou l pa pa blese w <br>
Mwen pa moun pasyan sa <br>
Ki ap padone w <br>
Tout mankman w <br>
Paske li pè pèdi w <br>
Mwen pa moun sa <br>
Ou vle ki adore w tankou yon ti dye <br>
Paske w anvi santi w enpòtan <br>
Mwen pa moun sa <br>
Ki ap ba w tout bagay <br>
San l pa janm jwenn kichòy <br>
Mwen pa moun sa <br>
Ki ap toujou la pou ou <br>
Men lè l bezwen w <br>
Ou pa janm disponib <br>
Mwen pa moun sa <br>
Ou anvi m ye a <br>
Mwen renmen m twòp <br>
Pou m pa pèmèt mwen <br>
Tounen yon ti maryonèt <br>
Nan men w <br>
</p>
