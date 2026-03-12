#Appweb
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mi App Web</title>
<link rel="stylesheet" href="styles.css">
</head>

<body>

<div class="app">
  
    <header>
        <h1>Mi App Web</h1>
        <p>Práctica 1 - Sub 2</p>
    </header>

    <section class="card alumno">
        <img src="https://cdn-icons-png.flaticon.com/512/3135/3135715.png">
        <h2>Alumno</h2>
        <p>Escribe aquí tu nombre</p>
    </section>

    <section class="card opciones">
        <h2>Opciones</h2>

        <button>Inicio</button>
        <button>Perfil</button>
        <button>Tareas</button>
        <button>Ajustes</button>

    </section>

    <section class="card bienvenida">
        <h2>Bienvenido</h2>
        <p>
        Esta es una página web responsiva con apariencia de app móvil.
        Su diseño se adapta a la pantalla del celular o laptop.
        </p>
    </section>

    <footer>
        <span>🏠</span>
        <span>📋</span>
        <span>⚙️</span>
    </footer>

</div>

</body>
</html>
body{
    margin:0;
    font-family: Arial, Helvetica, sans-serif;
    background:#3f5c99;
    display:flex;
    justify-content:center;
}

.app{
    width:360px;
    background:white;
    border-radius:20px;
    padding:20px;
    margin:20px;
}

header{
    text-align:center;
}

header h1{
    color:#2f4d86;
    margin-bottom:5px;
}

header p{
    color:gray;
}

.card{
    background:#f1f2f6;
    border-radius:15px;
    padding:20px;
    margin-top:20px;
}

.alumno{
    text-align:center;
}

.alumno img{
    width:80px;
}

.opciones h2{
    margin-bottom:10px;
}

button{
    width:100%;
    padding:12px;
    margin:8px 0;
    border:none;
    border-radius:10px;
    background:#3f5c99;
    color:white;
    font-size:16px;
    cursor:pointer;
}

button:hover{
    background:#2f4d86;
}

.bienvenida p{
    color:#555;
}

footer{
    background:#3f5c99;
    color:white;
    border-radius:12px;
    margin-top:20px;
    padding:10px;
    display:flex;
    justify-content:space-around;
    font-size:22px;
}
