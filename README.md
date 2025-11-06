<!DOCTYPE  Zere Creative Studio>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descarga de Aplicaciones de Trabajo</title>
    <link rel="icon" type="image/png" href="Gemini_Generated_Image_r82afr82afr82afr.jpg">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background: #008a47; 
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        /* --- NUEVO ESTILO PARA EL CONTENEDOR DEL LOGO CENTRAL --- */
        .main-logo-container {
            text-align: center; /* Centra la imagen horizontalmente */
            margin: 30px 0;     /* Espacio arriba y abajo del logo */
        }
        .main-logo-container img {
            max-width: 250px;   /* Tamaño máximo del logo (ajústalo si quieres) */
            height: auto;
            border-radius: 15px; /* Bordes ligeramente redondeados para el logo */
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.2); /* Sombra para que resalte */
        }
        /* --- FIN DE ESTILO PARA EL LOGO CENTRAL --- */
        .search-bar {
            margin: 20px auto;
            text-align: center;
        }
        .search-bar input[type="text"]:focus,
        .search-bar button:focus,
        .download-button:focus {
            outline: 3px solid #007acc;
            outline-offset: 2px;
        }
        .search-bar input[type="text"] {
            width: 60%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 16px;
        }
        .search-bar button {
            padding: 10px 20px;
            background: #28a745;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }
        .search-bar button:hover {
            background: #218838;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
            border: 2px solid #dcdcdc; 
            border-radius: 12px;       
            padding: 25px;             
            background-color: #ffffff; 
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.1); 
        }
        .app {
            display: flex;
            align-items: center;
            background: white;
            padding: 20px;
            margin: 20px 0;
            border-radius: 10px; 
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.08); 
            border: 1px solid transparent; 
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out, border-color 0.3s ease-in-out;
        }
        .app:hover {
            transform: translateY(-8px); 
            box-shadow: 0 12px 25px rgba(0, 0, 0, 0.15); 
            border-color: #007acc; 
        }
        .app img {
            width: 80px;
            height: auto;
            margin-right: 20px;
        }
        .app h2 {
            color: #007acc;
        }
        .download-button {
            display: inline-block;
            padding: 10px 20px;
            background: #28a745;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .download-button:hover {
            background: #218838;
        }
        #statusMessage {
            text-align: center;
            color: #cc0000;
            font-weight: bold;
            margin-top: 15px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Descarga de Aplicaciones de Trabajo</h1>
        <p>Encuentra y descarga las mejores herramientas para tu trabajo creativo.</p>
    </header>

    <div class="main-logo-container">
        <img src="img/Gemini_Generated_Image_r82afr82afr82afr.png" alt="Logo de ZereApps Studio">
    </div>
    <div class="search-bar">
        <input type="text" id="searchInput" placeholder="Buscar aplicaciones..." onkeydown="handleSearchKey(event)" />
        <button type="button" onclick="searchApps()">Buscar</button>
        <div id="statusMessage" aria-live="polite"></div>
    </div>
    <div class="container" id="appContainer">
        <div class="app">
            <img src="img/Adobe Photoshop.png" alt="Icono de la aplicación Adobe Photoshop">
            <div>
                <h2>Adobe Photoshop</h2>
                <p>Photoshop es la herramienta de edición de imágenes más popular del mundo. Perfecta para diseñadores y fotógrafos.</p>
                <a href="https://www.adobe.com/products/photoshop.html" class="download-button">Descargar Photoshop</a>
            </div>
        </div>
        <div class="app">
            <img src="img/Adobe_Illustrator_CC_icon.svg.png" alt="Icono de la aplicación Adobe Illustrator">
            <div>
                <h2>Adobe Illustrator</h2>
                <p>Illustrator es la herramienta de diseño gráfico basada en vectores más utilizada. Ideal para crear ilustraciones y logotipos.</p>
                <a href="img/" class="download-button">Descargar Illustrator</a>
            </div>
        </div>
        <div class="app">
            <img src="img/Adobe_Indesign_CC_2026_icon.svg.png" alt="Icono de la aplicación Adobe InDesign">
            <div>
                <h2>Adobe InDesign</h2>
                <p>InDesign es una herramienta de diseño y maquetación utilizada para crear publicaciones impresas y digitales.</p>
                <a href="https://www.adobe.com/products/indesign.html" class="download-button">Descargar InDesign</a>
            </div>
        </div>
        <div class="app">
            <img src="img/coreldraw-logo_brandlogos.net_96dfz-512x512.png" alt="Icono de la aplicación CorelDRAW">
            <div>
                <h2>CorelDRAW</h2>
                <p>CorelDRAW es un software de diseño gráfico basado en vectores, ideal para crear ilustraciones y diseños gráficos.</p>
                <a href="https://www.coreldraw.com/en/product/coreldraw/" class="download-button">Descargar CorelDRAW</a>
            </div>
        </div>
        <div class="app">
            <img src="img/Sketch.jpg" alt="Icono de la aplicación Sketch">
            <div>
                <h2>Sketch</h2>
                <p>Sketch es una herramienta de diseño digital centrada en la creación de interfaces y prototipos.</p>
                <a href="https://www.sketch.com/" class="download-button">Descargar Sketch</a>
            </div>
        </div>
    </div>

    <script>
        function searchApps() {
            const input = document.getElementById('searchInput').value.toLowerCase();
            const apps = document.querySelectorAll('.app');
            const statusDiv = document.getElementById('statusMessage');
            let found = false;

            apps.forEach(app => {
                const title = app.querySelector('h2').textContent.toLowerCase();
                if (title.includes(input)) {
                    app.style.display = 'flex';
                    found = true;
                } else {
                    app.style.display = 'none';
                }
            });

            if (!found) {
                statusDiv.textContent = 'No se encontraron aplicaciones que coincidan con tu búsqueda.';
            } else {
                statusDiv.textContent = '';
            }
        }
        
        function handleSearchKey(event) {
            if (event.key === 'Enter') {
                searchApps();
            }
        }
    </script>
</body>
</html>
