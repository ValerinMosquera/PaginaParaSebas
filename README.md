# PaginaParaSebas
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ánimo, amor</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            text-align: center;
            padding-top: 50px;
        }
        .message {
            background-color: #fff;
            border-radius: 10px;
            padding: 20px;
            max-width: 600px;
            margin: 0 auto;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            transition: background-color 0.3s ease;
            margin-top: 20px;
        }
        button:hover {
            background-color: #45a049;
        }
        .interests {
            margin-top: 50px;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .interest {
            width: 30%;
            margin-bottom: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 10px;
            overflow: hidden;
        }
        .interest img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .interest-content {
            padding: 20px;
        }
        /* Animaciones */
        .kiss-animation {
            animation: blowkiss 1s infinite alternate;
        }
        .heart-animation {
            animation: heartbeat 1s infinite alternate;
        }
        @keyframes blowkiss {
            0% { transform: scale(1); }
            100% { transform: scale(1.2) rotate(-45deg); }
        }
        @keyframes heartbeat {
            0% { transform: scale(1); }
            100% { transform: scale(1.3); }
        }
    </style>
</head>
<body>
    <div class="message">
        <h1>Ánimo, Mi Amor</h1>
        <p>Quería recordarte lo especial que eres para mí. Aunque ahora te sientas triste, recuerda que siempre estoy aquí para apoyarte.</p>
        <p>Eres fuerte, valiente y capaz de superar cualquier obstáculo que se interponga en tu camino. No estás solo, juntos podemos enfrentar cualquier desafío.</p>
        <p>Recuerda que cada día es una nueva oportunidad para crecer, aprender y encontrar la felicidad. Mantén la cabeza en alto y sigue adelante con determinación.</p>
        <p>Te amo más de lo que las palabras pueden expresar. Siempre estaré aquí para ti, para celebrar tus alegrías y para sostener tu mano en los momentos difíciles.</p>
        <button onclick="window.location.href='https://youtu.be/wg41GeB6QbE?si=IltRh1uQS5gUCU8C'">Dar un toquecito</button>
        <button onclick="showKisses()">Besitos Pa' ti</button>
        <button onclick="showHearts()">Te amo</button>
    </div>

    <div class="interests">
        <div class="interest">
            <img src="https://i.blogs.es/09ac95/spider-man-spiderverso/1366_2000.jpeg" alt="Spider-Man">
            <div class="interest-content">
                <h2>Spider-Man</h2>
                <p>Nunca subestimes el poder de un buen superhéroe. Siempre recuerda que, al igual que Spider-Man, tienes la fuerza para superar cualquier desafío.</p>
            </div>
        </div>
        <div class="interest">
            <img src="https://phantom-marca-mx.unidadeditorial.es/bee2d21aff4ab87be99e65321fd09e91/resize/828/f/jpg/mx/assets/multimedia/imagenes/2024/04/03/17121389615994.jpg" alt="Fórmula 1">
            <div class="interest-content">
                <h2>Fórmula 1</h2>
                <p>El Nano también ha tenido altibajos, sus errores le han enseñado valiosas lecciones sobre la vida y el éxito. Recuerda que incluso los campeones tienen momentos difíciles, pero lo importante es aprender y seguir adelante con determinación.</p>
            </div>
        </div>
        <div class="interest">
            <img src="https://caracoltv.brightspotcdn.com/dims4/default/bfee61d/2147483647/strip/true/crop/900x601+0+0/resize/900x601!/quality/90/?url=http%3A%2F%2Fcaracol-brightspot.s3.amazonaws.com%2F88%2F6b%2F97e3feca4c429ef3a1690042e844%2Fcolp-298394.jpg" alt="Junior de Barranquilla">
            <div class="interest-content">
                <h2>Junior de Barranquilla</h2>
                <p>El Junior ha enfrentado numerosos desafíos en su trayectoria, pero siempre ha salido victorioso, ha seguido adelante con valentía y determinación. Al igual que este gran equipo, tienes un gran espíritu y juntos podemos superar cualquier desafío.</p>
            </div>
        </div>
    </div>

    <script>
        function showKisses() {
            alert('💋💋💋 ¡Besitos Pa\' ti! 💋💋💋');
        }
        
        function showHearts() {
            alert('❤️❤️❤️ Te amo ❤️❤️❤️');
        }
    </script>
</body>
</html>
