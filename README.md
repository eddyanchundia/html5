html5
!DOCTYPE HTML>
<html>

<header>
<center>
<h2>CONTRATO DE VENTA DE AUTOS</h2>
</center> 
<center> 
<img src=LOGOVENTADEAUTOS2.gif border=0> 
</center> 
</header>

<br>
<br>
<h2>video sobre modelo de autos a eleccion del cliente</h2>
<body>
<form action = "index.php" method = "get">
<form fieldset>
<video controls = "controls" width= "430" height= "320">
<source src= "carros.vlc" type="video/mp4">
<source src= "carros.oggtheora.ogv." type="video/mp4">
<source src= "carros.webm" type="video/mp4">
</video>

	<h1>Audio</h1>
<audio controls='control' loop='loop'>
<source src='FLO-RIDA_FT_TPAIN-_LOW.mp3' type='audio/mp3'/>
</audio>
<br>
<br>
<fieldset>
<legend> Informacion del cliente
</legend>
       
	Numero de cedula cliente <input type= "text" id="cedula"/><br> 
	Nombre de cliente <input type= "text" id="cliente"/><br> 
	E-mail:<input type = "email" name = "email" placeholder = "tu mail"/><br/>  
	
	<br>
	website: <input type = "url" name = "url" required = "required" autofocus/><br/>
	comentario<label>
	<textarea name = "Comentario"></textarea>
	<br>
	<br>
	
	Puntos: <input type = "number" name = "puntos" min="1" max="14" /><br/>
	Rango: <input type ="range" min="0" max="20" step="5"><br/>
	Data: <input type = "date" name = "data" ><br/>
	color: <input type = "color" name = "color" ><br/>
	
</fielsed>

<input type = "submit" />
</form>
<BODY BGCOLOR="orange"> 
</body>
<html>

web
