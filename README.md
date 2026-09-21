# para-johany
flores amarillas 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Flores para Johany 🌻</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            min-height: 100vh;
            overflow: hidden;
            background: linear-gradient(#87CEEB 0%, #dff6ff 65%, #8fd14f 65%);
            font-family: Arial, sans-serif;
        }

        .mensaje {
            position: absolute;
            top: 50px;
            width: 100%;
            text-align: center;
            z-index: 10;
            animation: aparecer 2s ease;
        }

        .mensaje h1 {
            color: #d89b00;
            font-size: 45px;
            text-shadow: 2px 2px 5px white;
        }

        .mensaje p {
            margin-top: 10px;
            font-size: 22px;
            color: #6b4b00;
        }

        .jardin {
            position: absolute;
            bottom: 0;
            width: 100%;
            height: 65%;
        }

        .flor {
            position: absolute;
            bottom: 80px;
            width: 100px;
            height: 200px;
            animation: balanceo 3s ease-in-out infinite;
            transform-origin: bottom;
        }

        .tallo {
            position: absolute;
            width: 8px;
            height: 150px;
            background: #287a35;
            left: 46px;
            top: 55px;
            border-radius: 10px;
        }

        .hoja {
            position: absolute;
            width: 45px;
            height: 20px;
            background: #319b40;
            border-radius: 100% 0;
        }

        .hoja.izq {
            left: 5px;
            top: 125px;
            transform: rotate(-25deg);
        }

        .hoja.der {
            right: 5px;
            top: 100px;
            transform: rotate(25deg) scaleX(-1);
        }

        .centro {
            position: absolute;
            width: 42px;
            height: 42px;
            background: #8b5200;
            border-radius: 50%;
            left: 29px;
            top: 30px;
            z-index: 2;
        }

        .petalo {
            position: absolute;
            width: 38px;
            height: 60px;
            background: #FFD21F;
            border-radius: 50%;
            left: 31px;
            top: 0;
            transform-origin: center 50px;
        }

        .p1 { transform: rotate(0deg) translateY(-18px); }
        .p2 { transform: rotate(45deg) translateY(-18px); }
        .p3 { transform: rotate(90deg) translateY(-18px); }
        .p4 { transform: rotate(135deg) translateY(-18px); }
        .p5 { transform: rotate(180deg) translateY(-18px); }
        .p6 { transform: rotate(225deg) translateY(-18px); }
        .p7 { transform: rotate(270deg) translateY(-18px); }
        .p8 { transform: rotate(315deg) translateY(-18px); }

        .flor1 {
            left: 10%;
            transform: scale(0.8);
            animation-delay: 0.2s;
        }

        .flor2 {
            left: 30%;
            transform: scale(1.1);
            animation-delay: 0.8s;
        }

        .flor3 {
            left: 50%;
            transform: scale(0.9);
            animation-delay: 0.4s;
        }

        .flor4 {
            left: 70%;
            transform: scale(1.2);
            animation-delay: 1s;
        }

        .flor5 {
            left: 88%;
            transform: scale(0.75);
            animation-delay: 0.6s;
        }

        .corazon {
            position: absolute;
            top: 180px;
            left: 50%;
            transform: translateX(-50%);
            font-size: 35px;
            animation: latido 1.2s infinite;
        }

        @keyframes balanceo {
            0%, 100% {
                rotate: -3deg;
            }

            50% {
                rotate: 3deg;
            }
        }

        @keyframes latido {
            0%, 100% {
                transform: translateX(-50%) scale(1);
            }

            50% {
                transform: translateX(-50%) scale(1.25);
            }
        }

        @keyframes aparecer {
            from {
                opacity: 0;
                transform: translateY(-30px);
            }

            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        .firma {
            position: absolute;
            bottom: 25px;
            width: 100%;
            text-align: center;
            color: white;
            font-size: 18px;
            z-index: 20;
            text-shadow: 1px 1px 3px #333;
        }
    </style>
</head>

<body>

    <div class="mensaje">
        <h1>🌻 Para Johany 🌻</h1>
        <p>Estas flores amarillas son para ti 💛</p>
        <div class="corazon">💛</div>
    </div>

    <div class="jardin">

        <!-- Flor 1 -->
        <div class="flor flor1">
            <div class="tallo"></div>
            <div class="hoja izq"></div>
            <div class="hoja der"></div>

            <div class="petalo p1"></div>
            <div class="petalo p2"></div>
            <div class="petalo p3"></div>
            <div class="petalo p4"></div>
            <div class="petalo p5"></div>
            <div class="petalo p6"></div>
            <div class="petalo p7"></div>
            <div class="petalo p8"></div>

            <div class="centro"></div>
        </div>

        <!-- Flor 2 -->
        <div class="flor flor2">
            <div class="tallo"></div>
            <div class="hoja izq"></div>
            <div class="hoja der"></div>

            <div class="petalo p1"></div>
            <div class="petalo p2"></div>
            <div class="petalo p3"></div>
            <div class="petalo p4"></div>
            <div class="petalo p5"></div>
            <div class="petalo p6"></div>
            <div class="petalo p7"></div>
            <div class="petalo p8"></div>

            <div class="centro"></div>
        </div>

        <!-- Flor 3 -->
        <div class="flor flor3">
            <div class="tallo"></div>
            <div class="hoja izq"></div>
            <div class="hoja der"></div>

            <div class="petalo p1"></div>
            <div class="petalo p2"></div>
            <div class="petalo p3"></div>
            <div class="petalo p4"></div>
            <div class="petalo p5"></div>
            <div class="petalo p6"></div>
            <div class="petalo p7"></div>
            <div class="petalo p8"></div>

            <div class="centro"></div>
        </div>

        <!-- Flor 4 -->
        <div class="flor flor4">
            <div class="tallo"></div>
            <div class="hoja izq"></div>
            <div class="hoja der"></div>

            <div class="petalo p1"></div>
            <div class="petalo p2"></div>
            <div class="petalo p3"></div>
            <div class="petalo p4"></div>
            <div class="petalo p5"></div>
            <div class="petalo p6"></div>
            <div class="petalo p7"></div>
            <div class="petalo p8"></div>

            <div class="centro"></div>
        </div>

        <!-- Flor 5 -->
        <div class="flor flor5">
            <div class="tallo"></div>
            <div class="hoja izq"></div>
            <div class="hoja der"></div>

            <div class="petalo p1"></div>
            <div class="petalo p2"></div>
            <div class="petalo p3"></div>
            <div class="petalo p4"></div>
            <div class="petalo p5"></div>
            <div class="petalo p6"></div>
            <div class="petalo p7"></div>
            <div class="petalo p8"></div>

            <div class="centro"></div>
        </div>

    </div>

    <div class="firma">
        Con mucho cariño para Johany 🌻💛
    </div>

</body>
</html>
