<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Mulish:ital,wght@0,200..1000;1,200..1000&display=swap"
        rel="stylesheet">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <main>

    <div class="corpo">

        <img id="astro" src="images/astro.png" alt="Imagem de um astronauta no espaço">
        <h1>Explore sem limites</h1>
        <p>Porque o aprendizado é contínuo</p>
        <img id="arrow" src="images/seta.png" alt="Seta apontando para baixo">

    </main>

</body>

<footer>© 2023 - Rocketseat Explorer</footer>
</div>

</html>



* {
  padding: 0;
  margin: 0;
  border: 0;
  box-sizing: border-box;
}

body {
  background: #f9f4fb;
}

body::before {
  color: #312d64;
  content: "";
  width: 100%;
  height: 1242;
  display: block;
  position: absolute;
}

.corpo {
  align-items: center;
  flex-direction: column;
  display: flex;
 
}

#astro {
  padding: 0 34px 17px;
}

h1 {
  font-family: "Mulish", sans-serif;
  font-size: 32;
  line-height: auto;
  font-style: bold;
  padding-bottom: 5px;
  color: #b52184;
  align-items: center;
}

p {
  font-family: "Mulish", sans-serif;
  font-size: 20px;
  line-height: auto;
  font-style: bold;
  color: #312d64;
}

#arrow {
  padding: 35px 186px 93px;
}

#planet {
    padding: 50px 39px 50px;
}