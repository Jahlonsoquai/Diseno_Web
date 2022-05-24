#### Script Formulario

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ejercicio Formulario</title>
</head>
<body>
    <h2>Formato de Registro</h2>
    <form action="https://formspree.io/f/mwkyyvag" method="POST">
                    
        <fieldset> <legend><p>Información Personal del Usuario.</p></legend>  
            Ingresa tú nombre completo.<br>
            <input type="text" name="nombre" minlength="10" maxlength="40"><br>
            Ingresa tú correo electrónico.<br>
            <input type="email" name="correo electrónico"><br>
            Escribe tú contraseña.<br>
            <input type="password" name="contraseña" id="password" minlength="6" maxlength="10"><br>
            Confirma tú contraseña.<br>
            <input type="password" name="contraseña" id="confirm" minlength="6" maxlength="10"><br>

            <p>Género: <br>
            <input type="radio" id="gender" name="gender" value="male"/>Masculino<br>
            <input type="radio" id="gender" name="gender" value="female"/>Femenino<br>
            <input type="radio" id="gender" name="gender" value="other"/>Otro<br></p>
            Escribe tú dirección:<br>
            <textarea rows="3" cols="30"></textarea> <br>
            <input type="submit" value="Registrar">
        </fieldset>
    </form>

</body>
</html>


![image](https://user-images.githubusercontent.com/91554777/170103427-2b681a6e-05b6-49f3-834b-c188ebf12fbb.png)
