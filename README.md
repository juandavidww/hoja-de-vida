<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curriculum Vitae - Juan David Gomez Pico</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        .container {
            width: 800px;
            margin: 20px auto;
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
        }
        .header, .section {
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
            margin-bottom: 10px;
        }
        .header img {
            float: left;
            margin-right: 20px;
        }
        .header h1 {
            margin: 0;
        }
        .section h2 {
            margin: 0 0 10px 0;
            color: #007BFF;
        }
        .section p {
            margin: 5px 0;
        }
        .skills, .languages {
            display: flex;
            flex-wrap: wrap;
        }
        .skill, .language {
            width: 48%;
            margin: 1%;
        }
        .progress {
            background-color: #e0e0e0;
            border-radius: 5px;
            overflow: hidden;
        }
        .progress-bar {
            background-color: #007BFF;
            height: 20px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <img src="photo.jpg" alt="Foto de Juan David Gomez Pico" width="150">
            <h1>Juan David Gomez Pico</h1>
            <p><strong>Correo electrónico:</strong> perrito1234perrito34@gmail.com</p>
            <p><strong>Teléfono:</strong> 3135562940</p>
            <p><strong>Dirección:</strong> Calle123#10-20</p>
            <p><strong>Fecha de nacimiento:</strong> 23 de noviembre de 2008</p>
            <p><strong>Lugar de nacimiento:</strong> Floridablanca, Santander</p>
            <p><strong>Nacionalidad:</strong> Colombiana</p>
            <p><strong>Estado civil:</strong> Unión libre</p>
        </div>

        <div class="section">
            <h2>Perfil</h2>
            <p>Soy un trabajador con poca experiencia laboral. Me apasionan las artes, los deportes, soy muy activo físicamente, me gusta la lectura y disfruto del cine y el anime. Me gustan los animales, no tengo alergias ni ninguna discapacidad o enfermedad.</p>
        </div>

        <div class="section">
            <h2>Formación</h2>
            <p><strong>Bachillerato:</strong> Educación básica y secundaria</p>
            <p>ene 2012 - nov 2025</p>
            <p><strong>Técnico:</strong> Técnico en gestión de la producción industrial en la formación técnica en programación de software</p>
        </div>

        <div class="section">
            <h2>Competencias</h2>
            <div class="skills">
                <div class="skill">
                    <p><strong>VS-Code</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 70%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <p><strong>Wordpress</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 80%;"></div>
                    </div>
                </div>
                <div class="skill">
                    <p><strong>DFD</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 50%;"></div>
                    </div>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>Idiomas</h2>
            <div class="languages">
                <div class="language">
                    <p><strong>Inglés</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 70%;"></div>
                    </div>
                </div>
                <div class="language">
                    <p><strong>Portugués</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 80%;"></div>
                    </div>
                </div>
                <div class="language">
                    <p><strong>Italiano</strong></p>
                    <div class="progress">
                        <div class="progress-bar" style="width: 50%;"></div>
                    </div>
                </div>
            </div>
        </div>

        <div class="section">
            <h2>Pasatiempos e intereses</h2>
            <p>Deporte (gym), leer, descansar/acostamiento</p>
        </div>

        <div class="section">
            <h2>Certificados</h2>
            <p><strong>Capacitación para el empleo - salud digital:</strong> ene 2024</p>
            <p><strong>Udemy - Programación:</strong> jun 2024</p>
            <p><strong>Capacitación para el empleo - lógica de programación:</strong> abr 2024</p>
        </div>
    </div>
</body>
</html>
