body{
	background: url(why-kei-8e2gal_GIE8-unsplash.jpg); 
	background-repeat: no-repeat;
	width: 100%;
	height: 100vh;
	font-size: 16px;
	font-family: "Roboto", sans-serif;
	color: black;
	margin:0;
	padding: 0;
	box-sizing: border-box;
}

/**************N A V B A R****************/

*{
	box-sizing: border-box;
	margin:0;
	padding: 0;
	background-color: #white; 
}


 li,a,button{
	color: white;
}

header{
	width: 1300px;
	margin: 0 auto;
	margin-top: 20px;
	display: flex;
	justify-content: space-between;
	align-items: center;
	padding: 10px 10px;
	background-color: rgba(255,255,255,0);
	}

#nav-logo{
	color: white;
	margin-left: 40px;
	padding: 5px; 
	cursor: pointer;
	font-size: 40px;
	font-family: "Century Gothic";

}

#nav-logo a{
	color: white;
	transition: all 0.3s ease 0s;
	text-decoration: none;
}

#nav-logo a:hover{
	color: rgb(20,20,20);
}

.nav-links{
	padding-right: 20px;
	list-style: none;
	margin-left: auto;
	font-weight: 300;
	text-decoration: none;

}

.nav-links li{
	
	padding-left: 20px;
	font-size: 14px;
	display: inline-block;
	font-weight: 600;
}

.nav-links  li  a {
	text-decoration: none;
	color: white;
	transition: all 0.3s ease 0s;
	
}

.nav-links li  a:hover{
	transition: all 0.3s ease 0s;
	text-decoration: underline;
	
}

/************LANDING-PAGE*************/

.container{
	margin: 0;
	padding: 0;
	width: 100%;
}

.row{
	padding: 0;
	margin:0; 
	width: 100%;
	
}
.column{
	position: relative;
	width: 100%;
	margin:0;
}

.column-50{
	position: relative;
	width: 50%;
	margin: 0;
	padding: 0;
}

#landing-container .container{
	height: 70vh;
	color: black;
	width:100%; 
	margin: 0 auto; 
}

#slogan{
	color: white;
	font-weight: 600;
	cursor: default;
	margin-top: 10px;
	margin-bottom: 10px; 
	margin-left: 20px;
	font-size: 40px;
}

#slogan:hover{
	transition: all 0.3s ease 0s;
	color: black;
}

#landing-container .container #more-page{
	margin-top: 20px;
}

#def-ulov h3{
	font-size: 16px;
	padding: 20px;
	cursor: default;
	color: white;
	line-height: 30px;
}

#def-ulov h3:hover{
	transition: all 0.4s ease 0.2s;
	color: black;
	background-color: white;
}

#input-column{
	display: flex;
	flex-direction: column;
}

#input-column input{
	margin-top: 20px;
}

input{
	box-shadow: 5px 5px 2px rgba(0,0,0,0.1);
	font-size: 16px;
	font-family: Roboto;
	border:1px solid black;
	border-radius: 5px;
	width: 300px;
	height: 40px;
}

select{
	box-shadow: 5px 5px 2px rgba(0,0,0,0.1);
	font-size: 20px;
	font-family: Roboto;
	border:1px solid black;
	border-radius: 5px;
	width: 300px;
	height: 40px;
}

#inner-column{
	margin-left: 50px;
	border:1px solid black;
	box-shadow: 5px 5px 5px rgba(0,0,0,0.2);
	box-sizing: content-box;
	width: 350px;

	align-items: center;
	padding: 30px;
	background-color: white;
	border-radius: 15px;
}

#inner-column section{
	align-items:  center;
}

#inner-column input{
	margin-top: 10px; 
}

#select-section{
	text-align: center;	
}

#select-section select{
	
	margin-bottom: 5px;
	text-align: center;
	margin-left: 0px;
}

.question-text{
	margin-top: 10px;
	font-size: 16px;
	font-weight: 600;
}

.question-text select{
	margin-bottom: 5px;
}

.input-button{
	font-weight: 600;
	text-align: center;
}



.option-text{

	text-align: center; 
}

#qidirish{

	display: flex;
	text-align: center;
	flex-direction: row;
	margin-top: 20px;
}

#qidirish button{

	margin-top: 10px;
	margin-bottom: 10px;
	font-size: 20px;
	color: white;
	width: 150px;
	border:0.5px;
	border-radius: 5px;
	height: 40px;
	background: black;
	font-weight: 600;
	font-family: Roboto,sans-serif;
}

#submit-button-row button {
	color: white;
	text-align: center;
}

/***************DRIVER-PAGE****************/

#driver-header{
	color: black;
	cursor: default;
	font-size: 40px;
	font-weight: 600;
	margin-bottom: 20px;
}

#driver-slogan{
	cursor: default;
	color: black;
	margin-top: 10px;
	font-size: 16px;
	font-weight: 600;
	line-height: 40px;
	margin-bottom: 20px;
}

#driver-slogan:hover{
	transition: all 0.3s ease 0.1s;
	color: black;
	background-color:white; 
}

#download-button{
	padding: 10px; 
	font-size: 16px;
	font-weight: 600;
	height: 50px;
	color: white;
	background-color: black;
	border:1px solid black;
	border-radius: 10px;
}
/******* FOOTER *****/

.footer-links a:hover{
	transition: all 0.3s ease 0s;
	text-decoration: none;
	text-decoration-style: 2px solid white; 
}
