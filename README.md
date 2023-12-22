<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Promoción</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: url('https://i.imgur.com/KBQGGvd.png') no-repeat center top fixed;
            background-size: cover;
            background-attachment: fixed;
            background-position: center bottom;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: #fff;
        }

        h1 {
            margin-bottom: 20px;
            background: url('https://i.imgur.com/DuoOXwM.png') no-repeat;
            background-size: contain;
            text-indent: -9999px; /* Oculta el texto */
            width: 300px; /* Ancho de la imagen */
            height: 100px; /* Altura de la imagen */
        }

        .social-links {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }

        .social-link {
            text-decoration: none;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            margin: 0 10px;
        }

        .discord {
            background-color: #7289da; /* Morado */
        }

        .instagram {
            background-color: #f27150; /* Naranja rosado */
        }

        .facebook {
            background-color: #4167b2; /* Azul rey */
        }

        .epals {
            background-color: #7e57c2; /* Morado entre azulado */
        }

        #paypal-btn {
            text-decoration: none;
            color: #fff;
            padding: 10px;
            border-radius: 5px;
            text-align: center;
            margin-top: 20px;
        }

        #paypal-email {
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <h1>Bienvenido a Mi Promoción</h1>

    <div class="social-links">
        <a href="LINK_A_TU_DISCORD" class="social-link discord">Discord</a>
        <a href="https://www.instagram.com/bxd_fxmboy/" class="social-link instagram">Instagram</a>
        <a href="https://www.facebook.com/Derp.Derp.01/" class="social-link facebook">Facebook</a>
        <a href="https://www.epal.gg/epal/2312340" class="social-link epals">E-pals</a>
    </div>

    <a href="https://www.paypal.com/paypalme/TU_USUARIO_PAYPAL" id="paypal-btn">Donación PayPal</a>
    <p id="paypal-email">Correo electrónico de PayPal: Culd1945@outlook.com</p>
</body>
</html>
