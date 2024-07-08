<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Brawl Stars Generator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Brawl Stars Generator</h1>
        </div>
    </header>
    <section class="hero">
        <div class="container">
            <h2>Erhalte kostenlose Juwelen und Münzen</h2>
            <form id="generator-form">
                <input type="text" placeholder="Benutzername" required>
                <select required>
                    <option value="">Plattform auswählen</option>
                    <option value="ios">iOS</option>
                    <option value="android">Android</option>
                </select>
                <button type="submit">Starten</button>
            </form>
        </div>
    </section>
    <section class="steps">
        <div class="container">
            <h2>So funktioniert es</h2>
            <div class="step">
                <h3>Schritt 1</h3>
                <p>Gib deinen Brawl Stars Benutzernamen ein</p>
            </div>
            <div class="step">
                <h3>Schritt 2</h3>
                <p>Wähle deine Plattform aus (iOS oder Android)</p>
            </div>
            <div class="step">
                <h3>Schritt 3</h3>
                <p>Klicke auf „Starten“ und folge den Anweisungen</p>
            </div>
        </div>
    </section>
    <footer>
        <div class="container">
            <p>&copy; 2024 Brawl Stars Generator. Alle Rechte vorbehalten.</p>
        </div>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #1c1c1c;
    color: white;
    padding: 1em 0;
    text-align: center;
}

.hero {
    background-color: #4CAF50;
    color: white;
    padding: 2em 0;
    text-align: center;
}

.container {
    width: 80%;
    margin: auto;
}

form {
    margin-top: 1em;
}

input, select, button {
    padding: 0.5em;
    margin: 0.5em 0;
    width: 100%;
    max-width: 300px;
    box-sizing: border-box;
}

button {
    background-color: #333;
    color: white;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #555;
}

.steps {
    padding: 2em 0;
    background-color: white;
    text-align: center;
}

.step {
    margin-bottom: 1em;
}

footer {
    background-color: #1c1c1c;
    color: white;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}
