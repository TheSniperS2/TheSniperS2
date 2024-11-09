/* Reset CSS básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
    min-height: 100vh;
    background-color: #f3f4f6;
    color: #333;
}

/* Encabezado */
header {
    text-align: center;
    margin-bottom: 20px;
}

header h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
    color: #111;
}

header p {
    font-size: 1.2em;
    color: #555;
}

/* Sección de redes sociales */
.social-media {
    display: flex;
    gap: 20px;
    margin-top: 20px;
}

.icon {
    width: 50px;
    height: 50px;
    display: inline-block;
    background-size: cover;
    background-repeat: no-repeat;
    filter: invert(20%);
    transition: filter 0.3s;
}

.icon:hover {
    filter: invert(50%);
}

/* Iconos personalizados */
.linkedin {
    background-image: url('https://cdn-icons-png.flaticon.com/512/174/174857.png');
}

.github {
    background-image: url('https://cdn-icons-png.flaticon.com/512/733/733553.png');
}

.gmail {
    background-image: url('https://cdn-icons-png.flaticon.com/512/732/732200.png');
}
