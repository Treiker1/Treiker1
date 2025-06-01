<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>¿Quieres ser mi enamorada?</titl>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #fff0f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      background: white;
      border-radius: 15px;
      padding: 30px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
      max-width: 400px;
    }
    .title {
      color: #d32f2f;
      font-size: 24px;
      margin-bottom: 15px;
    }
    .text {
      color: #333;
      font-size: 16px;
      margin-bottom: 30px;
    }
    .btn {
      font-size: 16px;
      padding: 10px 20px;
      margin: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .yes {
      background-color: #4caf50;
      color: white;
    }
    .no {
      background-color: #f44336;
      color: white;
    }
  </style>
</head>
<body>
  <div class="card">
    <div class="title">¿Quieres ser mi enamorada?</div>
    <div class="text">
      Solo quería decirte algo que me guardé por un tiempo.<br>
      Me gustas, y cada día que te veo, me gustas un poquito más. ❤️
    </div>
    <button class="btn yes" onclick="alert('¡Yay! 🥰')">Sí</button>
    <button class="btn no" onclick="alert('Esta opción no está disponible 😅')">No</button>
  </div>
</body>
</html>
