---
layout: post
image: <img src="/assets/img/Couv.png"/>
title:  "Innoncente"
date:   2021-04-28 15:37:16 -0400
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
<img src="/assets/img/iig.jpg"/> <br>
<p>J’ignorais que grosse pouvait être une insulte <br>
Avant que je me fasse traiter de la sorte par un inculte <br>
Je ne savais pas ce qu’étaient des bourrelets <br>
Avant qu’un magazine « féminin » disent qu’ils répugnaient <br></p>

<p>Je me trouvais magnifique <br>
Jusqu’à ce que le contraire ait été dit par un narcissique <br>
J’adorais mes vergetures <br>
Cette confiance m’a été dépouillé par un rustre <br></p>

<p>Je ne savais pas qu’il était nécessaire de faire des régimes<br>
Envahie par la déprime<br>
J’ai cru que ce n’était que mon seul secours <br>
Car c’est ce que m’ont fait croire les vautours <br></p>

<p>Anxieuse de ne pas être assez <br>
Par le fait de ne pas avoir de modèles qui me ressemblait j’étais agacé<br>
Pour répondre à leurs attentes, elle exige de moi que je sois différente<br>
Ça ou rien m’a-t-elle dit intransigeante <br></p>

<p>Je n’étais pas politiquement correcte <br>
Avec du recul j’ai trouvé cela abjecte<br>
Et puis MERDE, je fais ce que je veux <br>
Vous êtes surement envieux <br></p>

<p>Je suis différente et cela me plait <br>
Le peintre par excellence, avec son chevalet<br>
M’a ainsi faite, il y a de quoi être fière<br> </p>
