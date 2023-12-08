
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KIARA - Ropa</title>
    <style>
        /* Estilos modificados */

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            height: 100vh;
            margin: 0;
        }

        header {
            background-color: green; /* Cambio de color a verde */
            font-size: 36px; /* Tamaño del título más grande */
            margin-bottom: 20px; /* Espacio añadido abajo del título */
        }

        #buscador {
            position: absolute;
            top: 10px;
            right: 10px;
            display: flex;
            align-items: center;
        }

        #cuadro-busqueda {
            padding: 5px;
            border: 1px solid #333;
            border-radius: 5px;
            margin-right: 5px;
        }

        #lupa {
            width: 20px;
            height: 20px;
            cursor: pointer;
        }

        section {
            display: flex;
            justify-content: center;
            align-items: center;
            flex-wrap: wrap;
        }

        .producto {
            width: 240px;
            height: 240px;
            margin: 20px;
            display: inline-block;
            vertical-align: top;
            transition: transform 0.3s ease;
        }

        .producto img {
            width: 100%;
            height: 100%;
        }

        .producto:hover {
            transform: scale(1.2);
        }

        .texto-precio {
            text-align: center;
            margin-top: 10px;
            font-family: 'Arial', sans-serif;
            font-size: 16px;
            color: #333;
        }

        .ofertas-especiales {
            background-color: black; /* Fondo negro */
            color: white; /* Texto blanco */
            padding: 20px;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            line-height: 1.5;
            width: 100%;
            box-sizing: border-box;
            margin-top: 20px; /* Espacio añadido arriba de las ofertas especiales */
            margin-bottom: 20px; /* Espacio añadido abajo de las ofertas especiales */
        }

        .terminos-condiciones {
            background-color: black; /* Fondo negro */
            color: white; /* Texto blanco */
            padding: 20px;
            font-family: 'Arial', sans-serif;
            font-size: 18px;
            line-height: 1.5;
            width: 100%;
            box-sizing: border-box;
            margin-top: 20px; /* Espacio añadido arriba de los términos y condiciones */
            margin-bottom: 20px; /* Espacio añadido abajo de las ofertas especiales */
        }
    </style>
</head>
<body>

    <header>
        KIARA
    </header>

    <div id="buscador">
        <input type="text" id="cuadro-busqueda" placeholder="Buscar...">
        <img id="lupa" src="https://imgur.com/lupa_icono.png" alt="Icono de lupa">
    </div>

    <section class="ofertas-especiales">
        Aprovecha estos descuentos por Navidad, ¡son una locura!
    </section>

    <section>
        <h2>Ofertas Especiales</h2>

        <div class="producto">
            <img src="https://source.unsplash.com/240x240/?clothing,blue" alt="Polo de lana azul">
            <div class="texto-precio">
                <p>Polo de lana azul</p>
                <p>Precio: S/ 99</p>
            </div>
        </div>

        <div class="producto">
            <img src="https://source.unsplash.com/240x240/?clothing,white" alt="Polo blanco bonito">
            <div class="texto-precio">
                <p>Polo blanco bonito</p>
                <p>Precio: S/ 79</p>
            </div>
        </div>

        <!-- Imágenes restauradas -->
        <div class="producto">
            <img src="https://source.unsplash.com/240x240/?clothing,red" alt="Polo rojo elegante">
            <div class="texto-precio">
                <p>Polo rojo elegante</p>
                <p>Precio: S/ 89</p>
            </div>
        </div>

       
