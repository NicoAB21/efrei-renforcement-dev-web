# Suivi — après-midi J1

**Noté. Un fichier par étudiant, écrit avec vos mots.** Une phrase honnête (« j'ai essayé X, j'ai vu Y, je ne comprends pas pourquoi ») rapporte plus qu'une phrase parfaite recopiée.

- Nom :ARCHAMBAULT--BONNET Nicolas
- Binôme : KARAOUNI Kelyan
- Atelier utilisé (le mien, celui du binôme, la reprise) : Mien

## Pour chaque TP abordé

Recopiez ce bloc autant de fois que nécessaire.

### TP06

- J'ai prédit : je n'ai rien trouvé à prédire
- Nous avons fait : on a formé le binôme, gardé mon atelier, j'ai lancé npm start depuis atelier et fait le commit depuis la racine
- J'ai observé : tout a marché du premier coup, le formulaire s'affiche et l'envoi change le statut, la liste reste vide mais c'est normal
- J'ai compris : qu'un formulaire recharge la page par défaut si on ne le bloque pas
- Je n'ai pas compris : rien il n'y a eu aucun problème sur ce TP
- Réponse à la question « Dans le suivi » du TP : la ligne event.preventDefault() dans l'écouteur submit

### TP07

- J'ai prédit : je pense qu'il suffit de créer un li et de l'ajouter à la liste
- Nous avons fait : j'ai tapé les event js pour récupérer le message entré et l'afficher dans la liste, avec un refus si le texte est vide
- J'ai observé : le message s'affiche et le champ se vide, un message fait que d'espaces est refusé et <b>gras</b> s'affiche avec les chevrons
- J'ai compris : qu'il est important de gérer le texte pour pas le faire analyser comme des balises html
- Je n'ai pas compris : rien de bloquant
- Réponse à la question « Dans le suivi » du TP : si on avait mis innerHTML la balise aurait été lue comme du code html et le mot serait apparu en gras

### TP08

- J'ai prédit : rien à prédire
- Nous avons fait : les deux fonctions : celle pour valider un message et l'autre pour envoyer des réponses précises en fonction de l'input
- J'ai observé : que si on veut faire un vrai chatbot IA la méthode actuelle serait impossible
- J'ai compris : qu'il faut bien faire attention aux inputs des users
- Je n'ai pas compris : rien que je n'ai pas compris
- Réponse à la question « Dans le suivi » du TP : je crois que on ne peut pas utiliser document dans le code qui tourne sur le serveur car sinon il faudrait que le serveur ait accès tout le temps à tout le contenu du navigateur de l'user

## Épreuve de l'explication (TP12)

- Ce que je n'ai pas su expliquer :
- Ce que mon binôme n'a pas su expliquer :

## Trois questions

1. Pourquoi `textContent` et pas `innerHTML` ?
2. Pourquoi trois fichiers plutôt qu'un seul ?
3. Si demain une IA écrit une partie du code, comment saurai-je qu'il est correct ?

## Aides utilisées

- Indices, aide-mémoire, voisins :
- Ce que j'ai demandé à une IA, et comment j'ai vérifié sa réponse :
