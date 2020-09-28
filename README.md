<!DOCTYPE html>
<html>
<meta charset="utf-8">
<head>
	<meta name="viewport" content="width=device-width, initial-scale 1.0">
	<meta http-equiv="X-UA-Compatible" content="ie-edge">
	<title>Ulov.</title>
	<link rel="stylesheet" type="text/css" href="portfolio-website.css">
	<script data-require="jquery@3.1.1" data-semver="3.1.1" src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
    <link rel="stylesheet" href="style.css" />
    <script src="script.js"></script>
</head>
<body>
<header>
	<div id="nav-logo" style="font-weight: 600">
		<a href="#">
			Ulov.
		</a>
	</div>
	<section class="nav-links">
		<ul>
			<li>
				<a href="#">XAVFSIZLIK</a>
			</li>
			<li>
				<a href="#">YANGI YO'NALISH QO'SHISH</a>
			</li>
			<li>
				<a href="#">RO'YHATDAN O'TISH</a>
			</li>
		</ul>
	</section>
</header>

<!--LANDING-PAGE-->

<section id="landing-container">
	<div class="container" style="height: 80vh;display: flex;">
			<div class="column-50" id="def-ulov" style="color: white; padding: 30px ; ">
				<div  id="slogan">
					<h1>
						Haqiqiy sayohatni his eting.
					</h1>
				</div>
				<h3 style="margin-top: 20px; width: 70%; ">
					Shahardan shaharga safarlar har doim mashaqqatli bo'lgan. Mashinani buyurtma berishdan tortib safaringizni o'zi ko'pgina qiyinchilik to'g'diradi. O'rtacha 2 soat ketadigan safaringiz keraksiz 4 yoki 5 soatga cho'zilib ketadi. Endi unday emas! <span style="font-family: Century Gothic">Ulov.</span> platformasida shahardan shaharga safarlaringiz uchun joy buyurtma bering va farqini o'zinigiz ko'ring.
				</h3>
			</div>
			<div class="column-50"  style=" padding: 20px; align-items: center;" >
				<section id="inner-column" style="align-items: center;">
				<section>
					<h1 style="text-align: center; font-size: 34px; margin-bottom: 20px;">Buyurtma berish</h1>
					<div class="input-button">
					<div class="question-text" style="margin-bottom: 5px;">Qaysi shahardan safar qilmoqchisiz:</div>
					<input placeholder=" Qayerdan" type="text" name="search">
					</div>
					<div class="input-button" style="margin-bottom: 10px; margin-top: 20px;">
					<div class="question-text">Qaysi shaharga bormoqchisiz:
					<input placeholder=" Qayerga" type="text" name="search">
					</div>
					</div>
				</section>
				<section id="select-section" style="margin-top: 20px;">
					<div>
					<div class="question-text"style="margin-bottom: 10px">Safar qachon bo'lib o'tadi:</div>
					<select>
						<option class="option-text">Bugun</option>
						<option class="option-text">Ertaga</option>
					</select>
					</div>
					<div>
					<div class="question-text" style="margin-bottom: 10px;margin-top: 20px;">Yo'lovchilar soni:</div>
					<select>
						<option class="option-text">1</option>
						<option class="option-text">2</option>
						<option class="option-text">3</option>
						<option class="option-text">4</option>
					</select>
					</div>
						<div  id="qidirish" style="text-align: center;" >
	  					<button style="text-align: center; margin-left: 100px;" type="submit" class="btn btn-primary option-menus"> 
	  					<a href="#" style="text-decoration: none; ">
	  						QIDIRISH
	  					</a></button>
	  					</div>
				</section>
				</section>
			</div>

	</div>
</section>

<!-- DRIVER-PAGE -->

<section style="background:white;width: 100%;">
	<div class="container" style="height: 100vh;display: flex; margin-top: 40px; ">
		<div class="column-50" style="padding: 40px;">
			<div id="driver-header"> 
			<div class="row" >	Ulovingiz bormi? 
			<div class="row"  >	Unda <span style="font-family: Century Gothic"> Ulov.</span > bilan pul ishlab toping!</div>
			</div>
			<div id="driver-slogan" style="width: 70%;" >
				Har kuni mijoz ohtarib charchadingizmi? Har kuni avtobekatda kutib turishdanchi? Ayniqsa yozning jazirama va 	qishning sovuq kunlarida! Tanish holatmi? Unda <span style="font-family: Century Gothic"> Ulov.</span > ilovasini hoziroq yuklab oling va bu holatlarni esdan chiqaring!
			</div>
			<div>
				<button id="download-button" style="cursor: pointer;">Ilovani yuklab olish</button>
			</div>
			</div>
		</div>
			

		<div class="column-50" style="background:url(marginalia-car-rental.png);background-repeat: no-repeat; margin-top: 50px;">
		</div>
	</div>

</section>


<!-- FOOTER -->	

<footer style=" font-size: 26px;font-weight: 600;padding: 50px;background-color: black;width: 100%;">
	<div class="container">
	<div style="display: flex;padding-left: 20px">
		<div class="footer-links" style="list-style: none;"><a style="color: white;cursor: pointer;" href="#"> Kompaniya haqida</a></div>
		<div class="footer-links" style="list-style: none;padding-left: 20px;"><a style="color: white;cursor: pointer;" href="#"> Hamkorlik</a></div>
		<div class="footer-links" style="list-style: none;padding-left: 20px;"><a style="color: white;cursor: pointer;" href="#"> Xavfsizlik</a></div>
		<div class="footer-links" style="color: white; list-style: none;padding-left: 20px; margin-left: auto;">©2020 Copyright <span style="font-family: Century Gothic"> Ulov.</span></div>
	</div>
	</div>
</footer>

</body>
</html>
