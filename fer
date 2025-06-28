<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ZOÉ - LOVE</title>
    <style>
        body {
            background-color: #ffc0cb; /* Rosa pastel */
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            font-family: Arial, sans-serif;
            overflow: hidden;
            margin: 0;
        }

        h1 {
            color: #fff;
            text-shadow: 2px 2px 4px #00000050;
        }

        button {
            background-color: #ff69b4;
            border: none;
            color: white;
            padding: 15px 30px;
            text-align: center;
            text-decoration: none;
            font-size: 20px;
            border-radius: 30px;
            cursor: pointer;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
            transition: transform 0.2s;
        }

        button:hover {
            transform: scale(1.1);
        }

        .heart {
            position: absolute;
            width: 20px;
            height: 20px;
            background: red;
            transform: rotate(-45deg);
            animation: float 6s infinite ease-in;
        }

        .heart::before,
        .heart::after {
            content: '';
            position: absolute;
            width: 20px;
            height: 20px;
            background: red;
            border-radius: 50%;
        }

        .heart::before {
            top: -10px;
            left: 0;
        }

        .heart::after {
            left: 10px;
            top: 0;
        }

        @keyframes float {
            0% {
                transform: translateY(0) rotate(-45deg);
                opacity: 1;
            }
            100% {
                transform: translateY(-600px) rotate(-45deg);
                opacity: 0;
            }
        }
    </style>
</head>
<body>

    <h1>Bienvenida TE AMO </h1> 
    <button onclick="redirigir()">Toca aquí</button>

    <script>
        function redirigir() {
            window.location.href = 'https://open.spotify.com/track/3kDb3VdpZsa70VjlG70Onf';
        }

        function crearCorazon() {
            const heart = document.createElement('div');
            heart.classList.add('heart');
            heart.style.left = Math.random() * window.innerWidth + 'px';
            heart.style.animationDuration = (3 + Math.random() * 3) + 's';
            document.body.appendChild(heart);
            setTimeout(() => heart.remove(), 6000);
        }

        setInterval(crearCorazon, 300);
    </script>

</body>
</html>
