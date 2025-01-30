<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bienvenue sur tyteoweb.com !</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur tyteoweb.com !</h1>
    </header>
    <main><br><br>
        <p>Hi this is my website welcome !</p>
        <button id="myButton">Cliquez-moi</button>
    </main>
    <footer>
        <p>&copy; 2025 tyteoweb.com</p>
    </footer>
    <script src="scripts/main.js"></script>

<style>  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color : #f0f0f0;
}
h1 {
    background-color: blueviolet;
    color: white;
    padding : 15px;
    text-decoration: solid 5px orange;
    height : 50px;
    text-align: center;
    font-size : 36px;
    border-bottom: 4px solid orange;
    text-shadow: 2px 2px 5px rgba(0,0,0,0.2); 
}
#a {
    text-align: center;
    font-size: 35px;
    text-decoration: underline wavy rgb(225.201.201);
}
#b {
    font-size: 35px;
    text-align: center;
}
#c {
    font-size: 25px;
    text-align: center;
    font-weight: normal;
}
#d {
    font-size: 25px;
    text-align: right;
    margin-left: 50px;
    margin-right: 50px;
}
header {
    text-align: center;
    height: 50px;
    background: linear-gradient(45deg, #ff8e43, #ff7d27);
    padding: 20px;
    box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.1);
    color: white;
}
#montagne {
    height: 500px;
    border: 1px solid rgb(155, 113 , 113);
    border-radius: 25px;
}
.montagne-container {
    display: flex;
    align-items: center;
}
#lien {
    text-align: center;
    margin-bottom: 375px;
}
.b { 
    display: flex;
    justify-content: right;
    align-items: center;
}
.a, .c, .d {
    display: flex;
    justify-content: center;
    align-items: center;
}
.b, .c {
    margin-bottom: 10px;
}
.button, .button2 {
    display: inline-block;
    padding: 10px 20px;
    background-color: #007bff;
    color: white;
    text-align: center;
    text-decoration: none;
    border-radius: 5px;
    font-size: 16px;
    transition: transform 0.2s ease-in-out;
}
.button:hover {
    background-color: #0056b3;
    transform: scale(1.08);
}
.button2 {
    background-color: #ff8e43;
    margin-bottom: -20px;
}
.button2:hover {
    background-color: #ff7d27;
    transform: scale(1.08);
}
</style>
    <p id="a">Bienvenue sur mon site!</p><br>
    <p id="b">Hi ! This is my website ! Here U can search, discuss,... and make everything about this website (but not bad things)
        
    Rules :<br>
-Discuss correctly<br>
-U can ask questions to me in the discuss bar or in the comments </p><br>
    <div class="montagne-container">
        <p id="d">Ici, c'est l'image d'une montagne, et vous pouvez retrouver la source juste en dessous de l'image directement.</p>
        <img src="https://thumbs.dreamstime.com/b/paysage-de-montagne-avec-ciel-%C3%A9toil%C3%A9-et-voie-laiteuse-%C3%A9l%C3%A9ments-cette-image-fournis-par-nasa-ai-g%C3%A9n%C3%A9r%C3%A9-307912006.jpg" id="montagne">
    </div>
    <div class="b">
        <a href="https://thumbs.dreamstime.com/b/paysage-de-montagne-avec-ciel-%C3%A9toil%C3%A9-et-voie-laiteuse-%C3%A9l%C3%A9ments-cette-image-fournis-par-nasa-ai-g%C3%A9n%C3%A9r%C3%A9-307912006.jpg" id="lien">Lien vers l'image</a>
    </div>
    <div class="c">
        <a href="https://cas.cybercolleges42.fr/login?service=https:%2F%2F0421490S.index-education.net%2Fpronote%2Feleve.html" class="button">Cliquez ici pour être envoyé vers le login de pronote (à travers cybercollège)</a>
    </div>
    <div class="d">
        <a href="https://0421490s.index-education.net/pronote/pageetablissement.html" class="button2">Cliquez ici pour être envoyé vers le site d'informations de pronote (et le lien pour accéder directement à pronote)</a>
    </div>
    <div class="e">
        <a href="https://m.youtube.com/" class="button3">Click here to go to Youtube !</a>
    </div>
    <div class="f">
        <a href="https://fr.wikipedia.org/wiki/Wikip%C3%A9dia:Accueil_principal"
        class="button4">Click here to go to Wikipedia !</a>
    </div>
    <!-- Add this section where you want the discussion bar to appear -->
<div class="discussion-bar">
    <h2>Discussion Bar</h2>
    <form id="discussionForm">
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" required><br><br>
        <label for="message">Message:</label>
        <textarea id="message" name="message" rows="4" cols="50" required></textarea><br><br>
        <button type="submit">Submit</button>
    </form>
    <div id="discussionMessages">
        <!-- Messages will appear here -->
    </div>
</div>
<p id="c">Enfin, si vous voulez retourner sur cette page, cliquez sur la flèche "<--" qui se trouve en haut à gauche de la page ^^</p>
</body>
</html>
