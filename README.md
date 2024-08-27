<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Link Up</title>
</head>
<body>
    <h4>Welcome to Link Up</h4>

    <button onclick="loginWithGoogle()">Login with Google</button>

    <script>
        function loginWithGoogle() {
            // Solicitar el nombre de usuario
            var username = prompt("Please enter your username:");
            
            if (username !== null && username !== "") {
                // Mostrar el nombre de usuario en una ventana emergente
                alert("Welcome, " + username + "!");
            } else {
                // Manejar el caso en el que el usuario no ingresa un nombre
                alert("No username entered.");
            }
        }
    </script>
</body>
</html>
