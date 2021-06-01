# Equipo-UWU
<!DOCTYPE html>
<html>
<title>The Wrong Reason</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<!-- <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css"> -->
<link rel="stylesheet" href="Estilos.css">
<link rel="stylesheet" href="Fuentes.css" type="text/css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.8.1/css/all.css" integrity="sha384-50oBUHEmvpQ+1lW4y57PTFmhCaXp0ML5d60M1M7uH2+nqUivzIebhndOJK28anvf" crossorigin="anonymous">
<link rel="stylesheet" href="popup.css">
<style>
.button {
  padding: 15px 25px;
  font-size: 16px;
  text-align: center;
  cursor: pointer;
  outline: none;
  color: #fff;
  background-color: #f44336;
  border: none;
  border-radius: 12px;
  box-shadow: 0 9px #be352b;
}

.button:hover {background-color: #f44336}

.button:active {
  background-color: #f44336;
  box-shadow: 0 5px #be352b;
  transform: translateY(4px);
}


body,h1,h2,h4,h5,h6 {font-family: "Raleway", sans-serif}
h3{
  font-family: "WrongFont";
  font-size: xx-large;
  font-weight: bold;
}
body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("WallpaperTru.jpg");
  min-height: 100%;
}

.w3-bar .w3-button {
  padding: 16px;
  
}
.w3-bar .w3-button {
  padding: 16px;
}
canvas{
  background-color: #255F85;

}
</style>
<body onLoad="javascript:showModal()">
<!-- Navbar (sit on top) -->
<div class="w3-top">
  <div class="w3-bar w3-card" id="myNavbar" style="color:rgb(255, 255, 255)!important;background-color:#797878!important">
    <a href="#home" class="w3-bar-item w3-button w3-wide" style="font-family: WrongFont; font-size: 22px;"><img src="abas.png"  width="200px" height="30px"></img></a> <!-- w3-bar-item -->
    
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small" id="headButton" style="font-family: WrongFont; font-size: 20px;">
      <a href="#about" class="w3-bar-item w3-button" style="padding: 18px;"><i class="fas fa-gamepad" style="padding-right: 5px;"></i>CARACTERÍSTICAS</a>
      <a href="#work" class="w3-bar-item w3-button" style="padding: 18px;"><i class="fa fa-th"></i> IMÁGENES</a>
      <a href="#pricing" class="w3-bar-item w3-button" style="padding: 18px;"><i class="fa fa-usd"></i> CONTRIBUCIONES</a>
      <a href="#team" class="w3-bar-item w3-button" style="padding: 18px;"><i class="fa fa-user"></i> EQUIPO</a>
      <a href="#contact" class="w3-bar-item w3-button" style="padding: 18px;"><i class="fa fa-envelope"></i> CONTACTO</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">EQUIPO</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class=" w3-jumbo w3-hide-small" style="font-family: WrongFont; font-size: 150px; padding-bottom: 0px;">The Wrong Reason</span><br> <!--w3-jumbo-->
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">The Wrong Reason</span><br>
    <span class="w3-large">Conoce la otra cara de la moneda</span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Colabora a crear su historia</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
   <a href="https://www.instagram.com/abaspistudio/"><i class="fab fa-instagram w3-hover-opacity"></i></a> 
    <i class="fab fa-twitter w3-hover-opacity"></i>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:80px 16px; background-color: #C5283D;" id="about">
  <h3 class="w3-center">SOBRE NUESTRO JUEGO</h3>
  <p class="w3-center w3-large">Principales características</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fas fa-dragon w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Sobrevive</p>
      <p>No bajes la guardia si no quieres convertirte en el saco de boxeo de otro preso. Lucha contra todos los presos y demuestra que eres más que fuerte para aguantar la vida diaria de un preso en la cárcel de máxima seguridad de Alaska. <br>Derrota a todos los jefes y consigue el puesto del jefe de la cárcel.</p>
    </div>
    <div class="w3-quarter">
      <i class="fas fa-hands-helping w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Interactua</p>
      <p>Tu poder no bastará para salir de este infierno, haz alianzas, ganate un respeto y consigue la confianza de otros presos para que te ayuden. <br> Conoce a todos los personajes, aprende de ellos, lucha en conjunto y quizás tengas una oportunidad aquí dentro.</p>
    </div>
    <div class="w3-quarter">
      <i class="fas fa-hand-rock w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large ">Entrena</p>
      <p>Esto no es el mundo real, aquí estás con los criminales más peligrosos del planeta, entrenate y mejora tus habilidades y poderes para estar a la altura. <br> Consigue puntos de habilidades para ir ampliando tus poderes e incluso aprendiendo los poderes de tus aliados o enemigos. ¡Las posibilidades son infinitas!</p>
    </div>
    <div class="w3-quarter">
      <i class="fas fa-key w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Escapa</p>
      <p>Toda puerta se abre ante la llave correcta, ¿serás capaz de escapar de este complejo o te pudrirás aqui dentro?</p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:100px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Tráiler oficial</h3>
      <p>Ya está disponible el primer tráiler oficial de presentación de The Wrong Reason<br>¡Deja tus impresiones al final de la página en los comentarios!</p>
      <p><a href="#work" class="w3-button w3-black"><i class="fa fa-th"> </i> Conoce los escenarios</a></p>
    </div>
    <div class="w3-col m6 ">
      <iframe width="560" height="315" src="https://www.youtube.com/embed/2oN1vjiyop0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      <!--<img class="w3-image w3-round-large" src="/w3images/phone_buildings.jpg" alt="Buildings" width="700" height="394">-->
    </div>
  </div>
  <div class="w3-container w3-light-grey" style="padding:30px 16px;">
    <div class="w3-row-padding w3-center w3-large">
      <p>Un grupo de criminales con habilidades especiales ha sido encerrado en una prisión de alta seguridad. ¿Por cuánto tiempo?</p>
      <p>A la alta seguridad de esta prisión se suman sus peligrosos criminales que la componen, averigua quien está de tu lado, usa tu instinto y descubre los secretos que te aguardan. ¿Puedes confiar en cualquiera? Necesitarás algo más que tus poderes para sobrevivir</p>
      
    </div>
	  <div class="w3-container w3-center">
		  <h3>Banda sonora oficial</h3>
	  <audio controls>
  
  <source src="MUltidef2.mp3" type="audio/mpeg">

</audio>
		 <p>Aquí podéis reproducir la banda sonora oficial de The Wrong Reason, una canción perfecta para acompañar al ritmo y la acción del videojuego.</p>
	  </div>
	  
  </div>
</div>

<div class="w3-container w3-dark-grey" style="padding:30px 16px; background-image: url(old-883672_1920.png); background-attachment: fixed;">
  <div class="w3-row-padding w3-center w3-large">
    <h3>PERSONAJES</h3>  
  </div>
  <div class="w3-row-padding " style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom flip-box">
      <div class=" flip-box-inner">
        <div class="flip-box-front">
          <img src="Alek Kleist.png" alt="Alek" style="width:100%">
        </div>
        <div class="flip-box-back" style="background-color: #C5283D;">
           <img src="Descripción Alek oscuro2.png" style="max-width: 100%;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom flip-box" style="max-width: 100%;">
      <div class="w3-card flip-box-inner">
        <div class="flip-box-front">
          <img src="Søren Nielsen.png" alt="Soren" style="width:100%">
        </div>
        <div class="flip-box-back" style="background-color: #C5283D;">
           <img src="Descripción Soren oscuro.png" style="max-width: 100%;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom flip-box" style="max-width: 100%; height: auto;">
      <div class="w3-card flip-box-inner">
        <div class="flip-box-front">
          <img src="Telum Alba.png" alt="Alex" style="width:100%">
        </div>
        <div class="flip-box-back" style="background-color: #C5283D;">
          <img src="Descripción Telum oscuro.png" style="max-width: 100%;">
       </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom flip-box" style="max-width: 50%;">
      <div class="w3-card flip-box-inner">
        
        <div class="flip-box-front">
          <img src="Monique Polgara.png" alt="Alvaro" style="width:100%">
          </div>
          <div class="flip-box-back">
            <img src="Descripción Monique oscuro.png" style="width: 100%;">
          </div>
      </div>
    </div>
  </div>
  <div class="w3-row-padding " style="margin-top:19%; margin-bottom: 19%;">
    <div class="w3-col l3 m6 w3-margin-bottom">
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom flip-box" style="max-width: 100%;">
      <div class="w3-card flip-box-inner">
        <div class="flip-box-front">
          <img src="Hayate Hidari.png" alt="Alex" style="width:100%">
        </div>
        <div class="flip-box-back" style="background-color: #C5283D;">
           <img src="Descripción Hayate oscuro.png" style="max-width: 100%;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom flip-box" style="max-width: 100%;">
      <div class="w3-card flip-box-inner">
        <div class="flip-box-front">
          <img src="Anya Karamasov.png" alt="Alex" style="width:100%">
        </div>
        <div class="flip-box-back" style="background-color: #C5283D;">
           <img src="Descripción Anya oscuro.png" style="max-width: 100%;">
        </div>
      </div>
    </div>
  </div>
	
</div>
  
<div class="w3-container w3-dark-gray" style="padding:30px 16px;">
  <h3 class="w3-center">Trajes</h3>
  <p class="w3-center w3-large" >Algunos de los diferentes atuendos que pueden llevar nuestros personajes<br>¡Arrastra el slider azul para cambiar el aspecto de los personajes!</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
      <div class="img-comp-img">
        <img src="Alek Informal2.png" style="width: 283.4px; height: 378px;" >
      </div>
      <div class="img-comp-img img-comp-overlay">
        <img src="Alek Preso2.png" style="width: 283.4px; height: 378px;">
      </div>
    </div>
    </div>
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
        <div class="img-comp-img">
          <img src="Soren informal2.png" style="width: 283.4px; height: 378px;" >
        </div>
        <div class="img-comp-img img-comp-overlay">
          <img src="Soren Presa2.png" style="width: 283.4px; height: 378px;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
        <div class="img-comp-img">
          <img src="Telum informal.png" style="width: 283.4px; height: 378px;" >
        </div>
        <div class="img-comp-img img-comp-overlay">
          <img src="Telum Preso2.png" style="width: 283.4px; height: 378px;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
        <div class="img-comp-img">
          <img src="Monique informal.png" style="width: 283.4px; height: 378px;" >
        </div>
        <div class="img-comp-img img-comp-overlay">
          <img src="Monique Presa.png" style="width: 283.4px; height: 378px;">
        </div>
      </div>
    </div>
  </div>

  <div class="w3-row-padding w3-section">
    <div class="w3-col l3 m6">
      <img  style="width:100%" onclick="onClick(this)" class="w3-hover-opacity">
    </div>
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
        <div class="img-comp-img">
          <img src="Hayate informal.png" style="width: 303.4px; height: 378px;" >
        </div>
        <div class="img-comp-img img-comp-overlay">
          <img src="Hayate Preso2.png" style="width: 303.4px; height: 378px;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6">
      <div class="img-comp-container">
        <div class="img-comp-img">
          <img src="Anya informal2.png" style="width: 283.4px; height: 378px;" >
        </div>
        <div class="img-comp-img img-comp-overlay">
          <img src="Anya Presa2.png" style="width: 283.4px; height: 378px;">
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6">
      <img  style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" >
    </div>
  </div>
</div>

<!-- Promo Section "Statistics" 
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">14+</span>
    <br>Partners
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">55+</span>
    <br>Projects Done
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">89+</span>
    <br>Happy Clients
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">150+</span>
    <br>Meetings
  </div>
</div>
-->

<!-- Work Section -->
<div class="w3-container" style="padding:128px 16px; background-color: orange" id="work">
  <h3 class="w3-center" style="font-size: 50px; color: white">CONCEPT ARTS</h3>
  <p class="w3-center" style="font-size: 20px; color: white">Aquí puedes echarle un vistazo al trabajo artístico del juego, el concepto de escenarios a implementar dentro del juego</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l4 m3">
      <img src="WhatsApp Image 2021-05-05 at 13.49.48.jpeg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Ala C">
    </div>
    <div class="w3-col l4 m3">
      <img src="WhatsApp Image 2021-05-06 at 07.19.10.jpeg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Ala D">
    </div>
    <div class="w3-col l4 m3">
      <img src="WhatsApp Image 2021-05-27 at 13.52.40.jpeg" style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Ala A">
    </div>
    
  </div>

  
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Skills Section -->
<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64" style="background-image: url(night-916275.png); background-size:cover">
  <div class="w3-row-padding" >
    <div class="w3-col m6" style="color: white;" >
      <h3>LLEVA LA AVENTURA MÁS ALLÁ</h3>
      <p>Estamos trabajando arduamente en pulir todos los aspectos del juego y que sea<br>
      una aventura apasionante para todos nuestros jugadores.</p>
      <p>Para que este juego llegue aún más lejos y se implenten aún más aspectos técnicos,<br>
	 el apoyo financiero de nuestros seguidores es muy importante. ¡Cada aporte mejorará el producto final y conllevará jugosas recompensas!</p>
		
    </div>
    <div class="w3-col m6" style="color: white">
      <p class="w3-wide"><i class="fas fa-gamepad"></i> Modo Multijugador</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:23%">230€</div>
      </div>
      <p class="w3-wide"><i class="fab fa-playstation"></i> Playstation Port</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:74%">743€</div>
      </div>
      <p class="w3-wide"><i class="fas fa-ghost"></i> Nuevos personajes</p>
      <div class="w3-grey">
        <div class="w3-container w3-dark-grey w3-center" style="width:12%">125€</div>
      </div>
    </div>
  </div>
</div>

<!-- Pricing Section -->
<div class="w3-container w3-center" style="padding:128px 16px; background-image:url(1901.png); background-size: cover;" id="pricing">
  <h3 style="font-size: 50px; color: white">SÉ PARTE DEL JUEGO</h3>
  <p style="font-size: 30px; color: white">¡Escoge un paquete y únete a nosotros!</p>
  <div class="w3-row-padding" style="margin-top:64px; padding: 0px 300px; ">
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow" style="border-radius: 40px;">
        <li class="w3-black w3-xxlarge w3-padding-32" style="border-radius: 30px;">Recién llegado</li>
        <li class="w3-padding-16" >Concept Arts </li>
        <li class="w3-padding-16">Póster "The Wrong Reason"</li>
        <li class="w3-padding-16">Acceso a beta cerrada</li>
        <li class="w3-padding-16">Chat directo con los desarrolladores</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">30€</h2>
          
        </li>
        <li class="w3-light-grey w3-padding-24" style="border-radius: 30px;">
			
			
				<button class="btn danger button" onClick="show()";>COMPRAR YA</button>
 

			<script>
// When the user clicks on div, open the popup
function show(){

document.getElementById("alerta").style.display = "inline";

}
</script>
         

        </li>
      </ul>
    </div>
    <div class="w3-third">
      <ul class="w3-ul w3-white w3-hover-shadow" style="border-radius: 40px;">
        <li class="w3-red w3-xxlarge w3-padding-48" style="border-radius: 40px;">JEFE DE LA PRISIÓN</li>
        <li class="w3-padding-16 w3-large">Paquete "Cadena Perpetua"</li>
        <li class="w3-padding-16 s">Aparición en créditos finales</li>
        <li class="w3-padding-16 s ">Jefe enemigo inpirado en ti (Implementado en Modo Multijugador)</li>
        <li class="w3-padding-16 s">Acceso a todo contenido extra y exclusivo</li>
        <li class="w3-padding-16 ">
          <h2 class="w3-wide">150€</h2>
          
        </li>
        <li class="w3-light-grey w3-padding-24" style="border-radius: 30px;">
         <button class="btn danger button" onClick="show()">COMPRAR YA</button>

        </li>
      </ul>
    </div>
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow" style="border-radius: 40px;">
        <li class="w3-black w3-xxlarge w3-padding-32" style="border-radius: 40px;">Cadena perpetua</li>
        <li class="w3-padding-16">Paquete "Recién llegado"</li>
        <li class="w3-padding-16">Charlas exclusivas de "The Wrong Reason"</li>
        <li class="w3-padding-16">Llavero exclusivo TWR </li>
        <li class="w3-padding-16">Mapa de la cárcel</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">60€</h2>
          
        </li>
        <li class="w3-light-grey w3-padding-24" style="border-radius: 30px;">
			
         <button class="btn danger button" onClick="show()">COMPRAR YA</button>

        </li>
      </ul>
    </div>
  </div>
</div>

<div class="alert w3-medio oculto" id="alerta" style="display: none; width: 50%;">
  <span class="closebtn" onclick="this.parentElement.style.display='none';">&times;</span> 
  <strong>¡Atención!</strong> Le recordamos que esta página simula la campaña de microfinanciación
  de un videojuego ficticio (no representa un producto real) por lo que usted no puede comprar nada.
</div>
<!-- Team Section -->
<div class="w3-container" style="padding:128px 16px; background-color: #C5283D;" id="team" >
  <h3 class="w3-center">NUESTRO EQUIPO</h3>
  <p class="w3-center w3-large">El equipo de desarrollo de The Wrong Reason</p>
  <div class="w3-row-padding w3-grayscale-min" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil diseñador.jpg" alt="Alex" style="width:100%">
        <div class="w3-container">
          <h3>Alejandro Campbell</h3>
          <p class="w3-opacity">Web Designer</p>
          <p>Programador y diseñador de nuestra pagina web oficial</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil artista.jpg" alt="Andrea" style="width:100%">
        <div class="w3-container">
          <h3>Andrea Gallardo</h3>
          <p class="w3-opacity">Art Director</p>
          <p>Directora de arte en el desarrollo de The Wrong Reason</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil Programadores.jpg" alt="Santiago" style="width:100%">
        <div class="w3-container">
          <h3>Santiago Meneses</h3>
          <p class="w3-opacity">Gameplay Programmer</p>
          <p>Co-Programador y co-diseñador de la página web oficial</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil director de sonido.jpg" alt="Alvaro" style="width:100%">
        <div class="w3-container">
          <h3>Alvaro Izquierdo</h3>
          <p class="w3-opacity">Music Director</p>
          <p>Director y compositor de los sonidos y música de The Wrong Reason</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
  </div>
  <div class="w3-row-padding w3-grayscale-min" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil Dibujante Digital.jpg" alt="Betu" style="width:100%">
        <div class="w3-container">
          <h3>Betuel Jivandec</h3>
          <p class="w3-opacity">Character Designer</p>
          <p>Diseñador y dibujante de los personajes en The Wrong Reason</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="Perfil Community Manager.jpg" alt="Puri" style="width:100%">
        <div class="w3-container">
          <h3>Purificación Méndez</h3>
          <p class="w3-opacity">Community Manager</p>
          <p>Community manager de las redes sociales oficiales de The Wrong Reason</p>
          <p><button class="w3-button w3-light-grey w3-block"><i class="fa fa-envelope"></i> Contactar</button></p>
        </div>
      </div>
    </div>
  </div>
</div>
<!--Preguntas Frecuentes (FAQ)-->
<div class="w3-container" style="padding:128px 16px; background-color: lightseagreen;">
  <h3 class="w3-center">Preguntas frecuentes (FAQ)</h3>
  <button class="accordion">¿Cuándo saldrá a la venta el juego?</button>
    <div class="panel">
      <p>Actualmente nuestro proyecto no se encuentra en una fase muy avanzada de producción, por lo que no sabemos todavía cuando podrá salir al mercado.</p>
    </div>

  <button class="accordion">¿Se me devolverá mi aportación si no se llega a los objetivos y finalmente el juego no sale a la venta?</button>
    <div class="panel">
      <p>Hasta que no estemos seguros de poder sacar el proyecto finalmente adelante no empezaremos a utilizar el dinero recibido por esta campaña de financiación, por lo que pueden estar tranquilos de que en tal caso tendrán su dinero.</p>
    </div>

  <button class="accordion">¿Esto es un proyecto real?</button>
    <div class="panel">
      <p>No, como ya hemos comentado previamente esta página simula la campaña de microfinanciación de un videojuego ficticio.</p>
    </div>
	<div class="w3-center" style="margin-top: 10px;"><button class="btn danger button"  onclick="on()">BIBLIOGRAFÍA</button></div>
	
</div>


<div class="overlays" id="overlays">
	<div class="text">
		<span class="closebtn" onclick="off()">&times;</span> 
	<h3>BIBLIOGRAFÍA DE RECURSOS USADOS</h3>
  <h4>IMÁGENES:</h4>
		
			<a class="li" href="https://www.freepik.es/vector-gratis/vista-frontal-ficha-policial-criminal-escala-medicion_5603551.htm#page=2&query=arresto&position=41">Fondo de sección "Contribuciones"</a>&nbsp;
  <a class="li" href="https://pixabay.com/es/photos/noche-ciudad-escaleras-barrotes-916275">Fondo de sección "Objetivos"</a><br>
    <a class="li" href="https://pixabay.com/es/photos/antigua-c%C3%A1rcel-construcci%C3%B3n-883672/">Fondo sección "Personajes"</a>&nbsp;
<a class="li" href="https://cdn.pixabay.com/photo/2017/04/13/18/48/drawing-2228403_1280.jpg">Imagen "Gameplay Programmer"</a><br>
		<a class="li" href="https://ec-global.es/wp-content/uploads/2018/01/mitos-community-manager.jpg">Imagen "Community Manager"</a>&nbsp;
    <a class="li" href="https://eresmama.com/wp-content/uploads/2020/11/nino-tocando-piano-musica-500x333.jpg">Imagen "Music Director"</a><br>
		<a class="li" href="https://eresmama.com/wp-content/uploads/2018/04/ordenador-freelancer-mujer-trabajo-casa-500x333.jpg">Imagen "Character Designer"</a>&nbsp;
		<a class="li" href="https://canalpress.net/wp-content/uploads/2020/12/canon-EOS-C70_Lifestyle_0023-500x333.jpg">Imagen "Web Designer"</a><br>
		<a class="li" href="https://eresmama.com/wp-content/uploads/2020/05/nino-pintando-acuarelas-500x333.jpg">Imagen "Art Director"</a>&nbsp;
		
		<h4>CÓDIGO USADO</h4>
		<a class="li" href="https://www.w3schools.com/howto/">W3 Schools</a>
 
   
	</div>
	</div>

	
	<script>
		function on() {
  document.getElementById("overlays").style.display = "block";
}

function off() {
  document.getElementById("overlays").style.display = "none";
}
	</script>
	

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTÁCTANOS</h3>
  <p class="w3-center w3-large">¿Tienes alguna duda sobre el juego?¿Quieres hablar directamente con nosotros? Envíanos un mensaje:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Madrid, España</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Teléfono: +34 601 23 45 67</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: thewrongreasonoficial@gmail.com</p>
    <br>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-border" type="text" placeholder="Nombre" required name="Name"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Asunto" required name="Subject"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Mensaje" required name="Message"></p>
      <p>
        <button class="w3-button w3-black" type="submit">
          <i class="fa fa-paper-plane"></i> ENVIAR MENSAJE
        </button>
      </p>
    </form>
  
    <!-- Image of location/map -->
    <!--<img src="Imagen prov abajo.jpg" class="w3-image w3-greyscale" style="width:100%;margin-top:48px">-->
  </div>
</div>

<div id="disqus_thread" class="w3-light-grey"></div>	
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = file:///C:/Users/menec/Desktop/Recursos2.0/Proto%20web.html;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = WR; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };*/
    
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://wrongreason.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

<!-- Disclaimer Pop-Up -->
<div class="overlay" id="overlay">
  <div class="popup" id="popup">
  <h3>DISCLAIMER</h3>
  <h4>Página realizada por: Equipo UWU (Equipo G)</h4>
  <p class="disclaimer">
  ATENCIÓN: Esta página simula la campaña de microfinanciación
            de un videojuego ficticio (no representa un producto real).
            Práctica de Multimedia, 1º GDDV - Curso 20/21 (Móstoles), URJC.
          La URJC no se hace responsable del contenido expuesto por el autor.
    
    
    </p>
<!-- Botón de "Entendido" -->
  <input type="submit" class="btn-submit" id="btn-submit" value="Entendido" onClick="closeModal()">		
  </div>
</div>
<!-- Integración de javascript para funciones del disclaimer -->
<script src="popup.js"></script>
	
	
<!-- Footer -->
<footer class="w3-center w3-padding-64" style="background-color: black; color: white;">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>Volver al principio</a>
  <div class="w3-xlarge w3-section">  
    <a href="https://www.instagram.com/abaspistudio/"><i class="fab fa-instagram w3-hover-opacity"></i></a>
    <i class="fab fa-twitter w3-hover-opacity"></i>
  </div>
 
</footer>
<script>
  /* Light YouTube Embeds by @labnol */
  /* Web: http://labnol.org/?p=27941 */
  document.addEventListener("DOMContentLoaded",
      function() {
          var div, n,
              v = document.getElementsByClassName("youtube-player");
          for (n = 0; n < v.length; n++) {
              div = document.createElement("div");
              div.setAttribute("data-id", v[n].dataset.id);
              div.innerHTML = labnolThumb(v[n].dataset.id);
              div.onclick = labnolIframe;
              v[n].appendChild(div);
          }
      });
  function labnolThumb(id) {
      var thumb = '<img src="https://i.ytimg.com/vi/ID/hqdefault.jpg">',
          play = '<div class="play"></div>';
      return thumb.replace("ID", id) + play;
  }
  function labnolIframe() {
      var iframe = document.createElement("iframe");
      var embed = "https://www.youtube.com/embed/VZzSBv6tXMw";
      iframe.setAttribute("src", embed.replace("ID", this.dataset.id));
      iframe.setAttribute("frameborder", "0");
      iframe.setAttribute("allowfullscreen", "1");
      this.parentNode.replaceChild(iframe, this);
  }
</script>

<script>
// Modal Image Gallery
function onClick(element) {
  document.getElementById("img01").src = element.src;
  document.getElementById("modal01").style.display = "block";
  var captionText = document.getElementById("caption");
  captionText.innerHTML = element.alt;
}


// Toggle between showing and hiding the sidebar when clicking the menu icon
var mySidebar = document.getElementById("mySidebar");

function w3_open() {
  if (mySidebar.style.display === 'block') {
    mySidebar.style.display = 'none';
  } else {
    mySidebar.style.display = 'block';
  }
}

// Close the sidebar with the close button
function w3_close() {
    mySidebar.style.display = "none";
}
</script>
<script>
  function initComparisons() {
    var x, i;
    /*find all elements with an "overlay" class:*/
    x = document.getElementsByClassName("img-comp-overlay");
    for (i = 0; i < x.length; i++) {
      /*once for each "overlay" element:
      pass the "overlay" element as a parameter when executing the compareImages function:*/
      compareImages(x[i]);
    }
    function compareImages(img) {
      var slider, img, clicked = 0, w, h;
      /*get the width and height of the img element*/
      w = img.offsetWidth;
      h = img.offsetHeight;
      /*set the width of the img element to 50%:*/
      img.style.width = (w / 2) + "px";
      /*create slider:*/
      slider = document.createElement("DIV");
      slider.setAttribute("class", "img-comp-slider");
      /*insert slider*/
      img.parentElement.insertBefore(slider, img);
      /*position the slider in the middle:*/
      slider.style.top = (h / 2) - (slider.offsetHeight / 2) + "px";
      slider.style.left = (w / 2) - (slider.offsetWidth / 2) + "px";
      /*execute a function when the mouse button is pressed:*/
      slider.addEventListener("mousedown", slideReady);
      /*and another function when the mouse button is released:*/
      window.addEventListener("mouseup", slideFinish);
      /*or touched (for touch screens:*/
      slider.addEventListener("touchstart", slideReady);
      /*and released (for touch screens:*/
      window.addEventListener("touchend", slideFinish);
      function slideReady(e) {
        /*prevent any other actions that may occur when moving over the image:*/
        e.preventDefault();
        /*the slider is now clicked and ready to move:*/
        clicked = 1;
        /*execute a function when the slider is moved:*/
        window.addEventListener("mousemove", slideMove);
        window.addEventListener("touchmove", slideMove);
      }
      function slideFinish() {
        /*the slider is no longer clicked:*/
        clicked = 0;
      }
      function slideMove(e) {
        var pos;
        /*if the slider is no longer clicked, exit this function:*/
        if (clicked == 0) return false;
        /*get the cursor's x position:*/
        pos = getCursorPos(e)
        /*prevent the slider from being positioned outside the image:*/
        if (pos < 0) pos = 0;
        if (pos > w) pos = w;
        /*execute a function that will resize the overlay image according to the cursor:*/
        slide(pos);
      }
      function getCursorPos(e) {
        var a, x = 0;
        e = e || window.event;
        /*get the x positions of the image:*/
        a = img.getBoundingClientRect();
        /*calculate the cursor's x coordinate, relative to the image:*/
        x = e.pageX - a.left;
        /*consider any page scrolling:*/
        x = x - window.pageXOffset;
        return x;
      }
      function slide(x) {
        /*resize the image:*/
        img.style.width = x + "px";
        /*position the slider:*/
        slider.style.left = img.offsetWidth - (slider.offsetWidth / 2) + "px";
      }
    }
  }
  </script>
  <script>
/*Execute a function that will execute an image compare function for each element with the img-comp-overlay class:*/
initComparisons();
</script>
<script>
  var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.maxHeight) {
      panel.style.maxHeight = null;
    } else {
      panel.style.maxHeight = panel.scrollHeight + "px";
    } 
  });
}
  </script>
</body>
</html>
