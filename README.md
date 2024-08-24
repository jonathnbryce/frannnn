<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Página de Amor</title>
    <style>
        body, html {
            height: 100%;
            margin: 0;
            font-family: Arial, sans-serif;
        }

        .background {
            background-image: url('img/fondo.avif'); /* Imagen de fondo */
            background-size: cover;
            background-position: center;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
        }

        .text {
            font-size: 72px; /* Aumenta el tamaño del texto */
            color: black; /* Cambia el color del texto a negro */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
            text-align: center;
            z-index: 1;
        }

        .rositas {
            position: absolute;
            width: 80px; /* Tamaño de las rositas */
        }

        .rosita-1 {
            top: 10%;
            left: 15%;
        }

        .rosita-2 {
            top: 10%;
            right: 15%;
        }

        .rosita-3 {
            bottom: 10%;
            left: 15%;
        }

        .rosita-4 {
            bottom: 10%;
            right: 15%;
        }

        .jake {
            position: absolute;
            bottom: 5%;
            right: 5%;
            width: 250px; /* Tamaño más grande de Jake */
        }
    </style>
</head>
<body>
    <div class="background">
        <div class="text"> Teeeeeeeeeeeeeeeee Amooooooo muchoooooooooooooooooooo Panchitaaaaaaaaaaaaa</div>
        
        <!-- Rositas -->
        <img src="img/rosass.png" alt="Rosita 1" class="rositas rosita-1"> 
        <img src="img/jakiiiii.png" alt="Rosita 2" class="rositas rosita-2">
        <img src="img/jakeee.png" alt="Rosita 3" class="rositas rosita-3">
        <img src="img/rosass.png" alt="Rosita 4" class="rositas rosita-4">

        <!-- Jake -->
        <img src="img/jake.png" alt="Jake" class="jake"> 
    </div>
</body>
</html>


