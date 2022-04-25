<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<link rel="stylesheet" href="style.css" />
		<link rel="icon" type="image/png" href="logo.png" />
		<title>Aviforêt</title>
	</head>
	<body>
		<header>
		<h1> Aviforêt </h1>
		</header>
		<p> Bienvenue en forêt <br/> Venez donc respirez.<p/> 
		<h2 class="sommaire"> Sommaire </h2>
		<ul>
		<li> <a class="link" href="#Contacte"> Contacter nous </a> </li>
		<li> <a class="link"href="#planing"> Planing </a> </li>
		</ul>
		<figure>
			<a href="forêt-image.jpg"><image class="grosse image" src="forêt-image-mini.jpg" alt="photo de forêt" /> </a>
			<figcaption> <em>forêt d'Orléans</em> </figcaption>
		</figure>
		<h2 id="Contacte"> Contacter nous</h2> 
		<p>	Vous souhaitez nous contacter? 
		Cliquer <a class="link" href="page2.html" title="cliqué pour nous contacter">ici</a> .</p>
		<h2 id="planing"> agenda </h2>	
		<p> 
			La forêt est en libre accès au public néanmoins il y a quelque règle concernant la découpe de bois.<br/>
			Tout public ne possède pas l'autorisation de pouvoir découpe du bois en forêt ce pourquoi nous mettons à disposition des horraire.
			<br/> <a class="link" href="test2.html" title="réserver vos horraires">Tableau horraire </a>
		</p>
		<h2 id="autorisation"> Vos autorisation et commande de QR code </h2>
		<p> <a class="link" href="commande.html"title="ici vous trouverez vos identifiant" >mon compte </a> </p>
		<footer>
			<img class="logo" src="logo.png" />
			<img class="logo" src="Republique-francaise-logo.png" />
		</footer>
	</body>
</html >

<css> 
	
h2, p
{
	color: white;
}

p, ul
{
	font-size: 1.2em;
	font-family: Verdana, sans-serif;
}

p, h2
{
	text-align: center;
}

.sommaire
{
	text-align: left;
}
 
 body
 {
	background-color: #084018;
	color: white;
 }
  
.link 
{
	color: #db7f1e; 
}

h1
{
	color: white;
	text-align: center;
	border: 6px #db7f1e outset;
	border-radius: 20px;
	box-shadow: 6px 6px 12px black;
}

img
{
	width: 750px;
	height: 750px;
}

footer
{
	border: 6px #db7f1e outset;
	border-radius: 10px;
}

.logo
{
	width: 150px;
	height: 150px;
	
}

</css>
