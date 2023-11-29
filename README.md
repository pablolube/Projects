<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cambiar Texto</title>
  <style>
    #texto {
      font-size: 18px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <h1 id="texto">Texto Original</h1>
  <button onclick="cambiarTexto()">Cambiar Texto</button>

  <script>
    function cambiarTexto() {
      var elementoTexto = document.getElementById("texto");
      if (elementoTexto.innerHTML === "Texto Original") {
        elementoTexto.innerHTML = "Nuevo Texto";
      } else {
        elementoTexto.innerHTML = "Texto Original";
      }
    }
  </script>
</body>
</html>
