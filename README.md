<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <title>Blagues drôles à volonté</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f9f9f9;
      color: #222;
      padding: 40px;
      text-align: center;
    }
    h1 {
      color: #2c3e50;
    }
    button {
      background-color: #3498db;
      border: none;
      padding: 15px 30px;
      font-size: 18px;
      color: white;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 25px;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #2980b9;
    }
    #blague {
      margin-top: 40px;
      font-size: 1.4em;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
      background: #ecf0f1;
      padding: 25px;
      border-radius: 12px;
      min-height: 100px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <h1>Bienvenue sur le site des blagues !</h1>
  <button onclick="nouvelleBlague()">Donne-moi une blague ! 😂</button>
  <p id="blague">Clique sur le bouton pour une blague hilarante.</p>

  <script>
    const blagues = [
      "Pourquoi les plongeurs plongent-ils toujours en arrière et jamais en avant ? Parce que sinon ils tombent dans le bateau.",
      "Quelle est la lettre la plus travailleuse ? Le T, parce qu'elle est toujours au travail.",
      "Pourquoi les squelettes ne se battent-ils jamais entre eux ? Parce qu'ils n'ont pas le cran.",
      "Qu'est-ce qui est jaune et qui attend ? Jonathan.",
      "Pourquoi est-ce que les poules n’ont pas de seins ? Parce que les coqs ont des ailes.",
      "Que dit une imprimante dans l'eau ? J’ai papier.",
      "Pourquoi les livres ont-ils toujours froid ? Parce qu’ils ont une couverture.",
      "Quel est le comble pour un électricien ? De ne pas être au courant.",
      "Pourquoi les vampires ne peuvent-ils pas bronzer ? Parce qu’ils ont peur du soleil.",
      "Comment appelle-t-on un chat tombé dans un pot de peinture le jour de Noël ? Un chat-peau claque.",
      "Pourquoi les policiers ne jouent-ils jamais à cache-cache ? Parce que même cachés, ils restent en service.",
      "Quelle est la nourriture préférée des électriciens ? Les courants d’air.",
      "Pourquoi les maths dépriment-elles ? Parce qu’elles ont trop de problèmes.",
      "Pourquoi les montagnes ne se battent-elles jamais ? Parce qu’elles sont toujours au sommet.",
      "Comment appelle-t-on un chien qui fait de la magie ? Un labracadabrador.",
      "Pourquoi les canards ont-ils autant de succès ? Parce qu’ils sont toujours dans le coin.",
      "Quel est le comble pour un jardinier ? De raconter des salades.",
      "Pourquoi les astronautes ne mangent-ils jamais de légumes ? Parce qu’ils préfèrent les étoiles filantes.",
      "Qu’est-ce qu’un escargot qui fait du vélo ? Un escargot rapide.",
      "Pourquoi les girafes ont-elles un long cou ? Parce que leurs pieds sentent mauvais.",
      "Quel est le comble pour un électricien ? De perdre son courant.",
      "Pourquoi les chaussures sont-elles mauvaises en sport ? Parce qu’elles ont toujours les pieds plats.",
      "Que fait une fraise sur un cheval ? Tagada tagada.",
      "Pourquoi les cochons ne savent-ils pas jouer aux cartes ? Parce qu’ils sont toujours dans la boue.",
      "Qu’est-ce qu’un poisson sans yeux ? Un poisson.",
      "Pourquoi les avions ne tombent-ils jamais ? Parce qu’ils ont des ailes.",
      "Que dit un oiseau à un autre ? T’es un peu bec.",
      "Pourquoi les éléphants ne bronzent-ils jamais ? Parce qu’ils ont peur des p'tites bêtes qui piquent.",
      "Comment appelle-t-on un vampire végétarien ? Un sanguinivore.",
      "Pourquoi les fantômes aiment les ascenseurs ? Parce qu’ils élèvent l’esprit.",
      "Quel est le comble pour un plombier ? De perdre la fuite.",
      "Pourquoi les chats détestent internet ? Parce qu’ils préfèrent les souris.",
      "Que fait un serpent quand il est fâché ? Il s’enroule.",
      "Pourquoi les abeilles ont-elles du mal à communiquer ? Parce qu’elles parlent en buzz.",
      "Quel est le comble pour un électricien ? De ne pas avoir de prise.",
      "Pourquoi les lapins sont-ils mauvais en math ? Parce qu’ils multiplient tout."
    ];

    function nouvelleBlague() {
      const index = Math.floor(Math.random() * blagues.length);
      document.getElementById('blague').textContent = blagues[index];
    }
  </script>
</body>
</html>
