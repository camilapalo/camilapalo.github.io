# camilapalo.github.io
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- IMPORTANTE PARA GOOGLE -->
    <title>Camila Palo | Portafolio Personal</title>

    <meta name="description"
    content="Página personal y portafolio de Camila Palo">

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, sans-serif;
        }

        body{
            background:#0f172a;
            color:white;
        }

        header{
            height:100vh;
            display:flex;
            flex-direction:column;
            justify-content:center;
            align-items:center;
            text-align:center;
            padding:20px;
        }

        h1{
            font-size:60px;
            margin-bottom:10px;
        }

        h2{
            font-size:25px;
            color:#94a3b8;
            margin-bottom:20px;
        }

        p{
            max-width:600px;
            line-height:1.6;
            font-size:18px;
        }

        .boton{
            margin-top:30px;
            padding:15px 30px;
            background:#3b82f6;
            color:white;
            text-decoration:none;
            border-radius:10px;
            transition:0.3s;
        }

        .boton:hover{
            background:#2563eb;
        }

        section{
            padding:80px 20px;
            text-align:center;
        }

        .card{
            background:#1e293b;
            padding:30px;
            border-radius:15px;
            max-width:500px;
            margin:auto;
            margin-top:20px;
        }
    </style>
</head>

<body>

    <header>

        <!-- IMPORTANTE PARA GOOGLE -->
        <h1>Camila Palo</h1>

        <h2>Estudiante de Ciencias de la Computación</h2>

        <p>
            Hola, soy Camila Palo. Esta es mi página web personal
            donde compartiré proyectos, programación y más.
        </p>

        <a href="#proyectos" class="boton">
            Ver proyectos
        </a>

    </header>

    <section id="proyectos">

        <h2>Mis proyectos</h2>

        <div class="card">
            <h3>Proyecto 1</h3>

            <p>
                Aquí puedes poner tus futuros proyectos
                de programación.
            </p>
        </div>

    </section>

</body>
</html>
