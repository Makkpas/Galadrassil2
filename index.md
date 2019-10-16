<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Inicio de Sesion</title>

    <link rel="stylesheet" href="./css/styleInicioSesion.css">

</head>

<body>
    <div class="app">
        <div class="login-form">
            <div class="form-container">

                <h2 class="login__title">Inicia Sesión</h2>

                <form class="login__form" autocomplete="on">
                    <input class="form__input" type="email" id="email" name="email" placeholder="Correo">
                    <input class="form__input" type="password" id="Password" name="password" placeholder="Contraseña">

                    <a href="contraseñaOlvidada.html" class="login__text login__text--link">¿Olvidó su contraseña?</a>

                    <div class="container-btn">
                        <button class="btn login__btn" type="submit">Iniciar Sesión</button>
                    </div>
                    <div class="container-btn registarse">
                        <a class="btn welcome__btn" href="registro.html">Registrarse</a>
                    </div>
                </form>

            </div>
        </div>

    </div>
</body>

</html>
