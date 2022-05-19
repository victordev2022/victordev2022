- 👋 Hi, I’m @victordev2022
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
victordev2022/victordev2022 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
mercearia para portifolio

<html>
  <head>
    <meta charset="UTF-8">
    <script src="script.js"></script>
    <!-- <link rel="stylesheet" type="text/css" href="styles.css"> -->
  </head>
  <body>
    <header>
  <img src="imagens/imagem.jpg">
  <figure> LOGO</figure>
  <h1>Mercadinho do Cleitinho</h1>
  <a href="/me.html">My other page</a>
    <input id="searchbar" onkeyup="search_animal()" type="text"
    name="search" placeholder="Search animals..">
    <ol id='list'>
    <li class="animals">Cat</li>
    <li class="animals">Dog</li>
    <li class="animals">Elephant</li>
    <li class="animals">Fish</li>
    <li class="animals">Gorilla</li>
    <li class="animals">Monkey</li>
    <li class="animals">Turtle</li>
    <li class="animals">Whale</li>
    <li class="animals">Aligator</li>
    <li class="animals">Donkey</li>
    <li class="animals">Horse</li>
</ol>
<script src="./animals.js"></script>
<style>
#searchbar{
  margin-left: 100%;
  padding:15px;
  border-radius: 10px;
}

input[type=text] {
   width: 30%;
   -webkit-transition: width 0.15s ease-in-out;
   transition: width 0.15s ease-in-out;
}
input[type=text]:focus {
  width: 70%;
}

#list{
 font-size:  1.5em;
 margin-left: 9px;
}

.animals{
display: list-item;    
} 
</style>
</header>
  </body>
</html>
