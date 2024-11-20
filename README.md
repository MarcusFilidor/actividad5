
<html lang="es">
<head>


<title> Menu desplegable </title>
<style type="text/css">

* {
padding: 0px;
margin: 0px;
}

#header {
margin: auto;
width: 500px;
font-family: Arial, Helvetica, sans-serif;
}

ul, ol {
list-style: none;
}

.nav li a{
background-color: #de2e03;
color: #fff;
text-decoration: none;
padding: 40px 20px;
display: block;
}

.nav li a: hover {
background-color: #000CC;
}

.nav > li {
float: left;
}

.nav li ul {
display: none;
position: absolute;
min-width:140px;
}

.nav li:hover > ul {
display: block;
}


</style>
</head>

<body>

<div id="header">
 
<ul class="nav">
  
    <li> <a href=""> Inicio </a> </li>

    <li> <a href=""> Servicios </a> 
        <ul>
             <li> <a href="https://marcusfilidor.github.io/actividad1/"> Diseño </a> </li>
             <li> <a href="https://marcusfilidor.github.io/actividad2/"> Desarrollo </a> </li>
             <li> <a href="https://google.com.mx"> SEO </a> </li>
        </ul>
    </li>   

    <li> <a href="https://marcusfilidor.github.io/actividad3/"> Acerca de </a> </li>
    <li> <a href="https://marcusfilidor.github.io/actividad4/"> Contacto </a> </li>
</ul>

</div>
</html>