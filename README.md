<!DOCTYPE html>
<html>
<head>
	<meta charset ="utf-8">
	<link href="test3.css"rel="stylesheet">
</head>
<body>
<div class="main">
	<div class="input">
		<fieldset>
			<legend>Вход в аккаунт</legend>
			<label>Email:<br/>
			<input type="text" name="Email"></label><br/>
			<label>Пароль:<br/>
			<input type="password"><br/>
		</fieldset>
		<form actiom="адрес получателя">
			<p>Поиск</p>
			<input type="search" name="poisk">
			<input type="submit" value="Поиск">
		</form>
	</div>
	<div class="content">
		<div class="h1">История жизни Децла</div>
		<div class="line">
			<p class="first">
			Децл родился в обеспеченной семье.</p>
			<p class="second">
			Его отец известный в прошлом режисер,
			именно он продвигал своего сына на российской сцене.
			</p>
		</div>
	</div>
	<div class="navigation">
		<div class="menu">
			<div class="music">
				Музыка
			</div>
		    <div class="video" >
		    	Видео
		    </div>
		    <div class="shop">
		    	Магазин
		    </div>	
	</div>
</div>
</body>
</html>
body{
	background:#55C9FF;
	color:#fff;
}
.h1{
	background:;
	width:; 
}
.line{
	background-color:;
}
.input,.content,.navigation{
	height: 700px;
	float:left;
}
.input{
	width: 19%;
}
.content{
	width: 60%;
}
.navigation{
	width: 19%;
}
form{
	margin-left:15px;
}
.first,.h1,.second{
	margin-left:10px;

}
.music,.video,.shop{
	width:100px;
	height:20px;
	background-color:#FF4B37;
	margin:5px;
	border-radius:5px;
	text-align:center;     
}
