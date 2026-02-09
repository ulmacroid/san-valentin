<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Para Ti 💖</title> 
<style>
body {
    margin: 0;
    height: 100vh;
    background: linear-gradient(135deg, #ff758c, #ff7eb3);
    display: flex;
    justify-content: center;
    align-items: center;
    font-family: 'Arial', sans-serif;
}.card {
    background: white;
    padding: 30px;
    border-radius: 20px;
    text-align: center;
    width: 90%;
    max-width: 350px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.25);
    animation: fadeIn 1.5s ease;
}

h1 {
    color: #e63946;
    margin-bottom: 10px;
}

p {
    color: #333;
    font-size: 16px;
}

button {
    margin-top: 15px;
    padding: 12px 25px;
    font-size: 16px;
    border: none;
    border-radius: 25px;
    background: #e63946;
    color: white;
    cursor: pointer;
    transition: transform 0.2s, background 0.2s;
}

button:hover {
    background: #c1121f;
    transform: scale(1.05);
}

@keyframes fadeIn {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
}
</style>
</head>

<body>

<div class="card">
    <h1>Hola, amor 💕</h1>
    <p>
        No soy bueno con las palabras,
        pero contigo todo tiene sentido.
        Gracias por llegar a mi vida y quedarte.
    </p>
    <p>
        Así que tengo una pregunta importante…
    </p>
    <h2>¿Quieres ser mi San Valentín? 🌹</h2>
    <button onclick="alert('Sabía que dirías que sí 💖 Te amo')">
        Sí, obvio 💘
    </button>
</div>

</body>
</html>
