<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Solicitud de Préstamo - M&T</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f2f5;
      margin: 0;
      padding: 0;
    }
    .container {
      max-width: 700px;
      margin: 40px auto;
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h1 {
      text-align: center;
      color: #333;
    }
    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
    }
    input, textarea, select {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      margin-top: 20px;
      width: 100%;
      padding: 15px;
      background-color: #007bff;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 16px;
      cursor: pointer;
    }
    button:hover {
      background-color: #0056b3;
    }
    img.logo {
      display: block;
      margin: 0 auto 20px;
      max-width: 200px;
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="logo.png" alt="Logo M&T" class="logo">
    <h1>Formulario de Solicitud</h1>
    <form action="https://formsubmit.co/darlynhfco19@gmail.com" method="POST" enctype="multipart/form-data">
      <label for="nombre">Nombre completo</label>
      <input type="text" id="nombre" name="nombre_completo" required>

      <label for="telefono">Teléfono</label>
      <input type="tel" id="telefono" name="telefono" required>

      <label for="cedula">Cédula</label>
      <input type="text" id="cedula" name="cedula" required>

      <label for="monto">Monto solicitado</label>
      <input type="number" id="monto" name="monto" required>

      <label for="foto">Foto de cédula</label>
      <input type="file" id="foto" name="cedula_foto" accept="image/*" required>

      <button type="submit">Enviar</button>
      <input type="hidden" name="_captcha" value="false">
      <input type="hidden" name="_next" value="https://formsubmit.co/thanks.html">
    </form>
  </div>
</body>
</html>
