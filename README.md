# free-
<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Free V-bucks</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            margin: 0;
            padding: 1em;
            background: #333;
            color: white;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
        }
        .content {
            padding: 2em;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>auf dieser website kann man free v-bucks bekommen</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Über mich</a>
        <a href="#contact">Kontakt</a>
    </nav>
    <div class="content">
        <h2>Home</h2>
        <p>um v-bucks zu bekommen gebe kontaktinformationen wie die telefonnummer ein ein passwort in der hinsicht wird nicht benötigt.</p>
        <h2>Über mich</h2>
        <p>Hier könntest du Informationen über dich hinzufügen.</p>
        <h2>Kontakt</h2>
        <p>Hier könntest du deine Kontaktinformationen hinzufügen.</p>
    </div>
    <footer>
        <p>&copy; 2024 Meine Webseite</p>
    </footer>
</body>
</html>


<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Passwortgeschützte Seite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .login-container {
            text-align: center;
            background-color: white;
            padding: 2em;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        input[type="password"] {
            padding: 0.5em;
            margin: 1em 0;
            width: 100%;
            box-sizing: border-box;
        }
        button {
            padding: 0.5em 2em;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        .error {
            color: red;
            margin-top: 1em;
        }
    </style>
</head>
<body>
    <div class="login-container">
        <h1>Passwort eingeben</h1>
        <input type="password" id="password" placeholder="Passwort">
        <button onclick="checkPassword()">Login</button>
        <p class="error" id="error"></p>
    </div>
    <script>
        function checkPassword() {
            var password = document.getElementById('password').value;
            var errorElement = document.getElementById('error');
            
            if (password === 'deinPasswort') {  // Ersetze 'deinPasswort' durch das gewünschte Passwort
                window.location.href = 'protected.html';  // Seite, zu der weitergeleitet wird
            } else {
                errorElement.textContent = 'Falsches Passwort. Bitte versuche es erneut.';
            }
        }
    </script>
</body>
</html>
