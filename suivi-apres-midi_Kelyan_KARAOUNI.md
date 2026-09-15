# Suivi — après-midi J1

**Noté. Un fichier par étudiant, écrit avec vos mots.** Une phrase honnête (« j'ai essayé X, j'ai vu Y, je ne comprends pas pourquoi ») rapporte plus qu'une phrase parfaite recopiée.

- Nom :KARAOUNI Kelyan
- Binôme : ARCHAMBAULT--BONNET Nicolas
- Atelier utilisé (le mien, celui du binôme, la reprise) : Binome

## Pour chaque TP abordé

Recopiez ce bloc autant de fois que nécessaire.

### TP06

- J'ai prédit : rien à prédire
- Nous avons fait : on a formé le binôme, on a comparé nos deux ateliers et gardé celui de Nicolas qui était plus avancé. Il tape en premier, je vérifie.
- J'ai observé : le serveur se lance bien et la page affiche le formulaire. Dans la console il y a juste le 404 sur favicon.ico.
- J'ai compris : que le commit sert à garder un point de départ propre avant de modifier le code.
- Je n'ai pas compris : rien, il n'y a eu aucun problème sur ce TP.
- Réponse à la question « Dans le suivi » du TP : la ligne event.preventDefault() dans l'écouteur submit.

### TP07

- J'ai prédit : je pense que la page va se recharger à chaque envoi et qu'on va perdre les messages.
- Nous avons fait : Nicolas a tapé le code et j'ai vérifié les identifiants #message et #messages avec index.html, puis j'ai testé les cas bizarres.
- J'ai observé : les messages s'empilent bien et la page ne se recharge pas. J'ai essayé avec que des espaces et c'est refusé
- J'ai compris : que trim enlève les espaces avant et après donc un message vide est bloqué
- Je n'ai pas compris : je ne vois pas bien la différence entre append et appendChild
- Réponse à la question « Dans le suivi » du TP : textContent affiche le texte tel quel, innerHTML aurait lu <b>gras</b> comme du html et le mot serait apparu en gras

### TP08

- J'ai prédit : rien à prédire
- Nous avons fait : le sujet nous dit de faire 2 fonctions donc on les a fait
- J'ai observé : q'u on pouvait réutiliser la fonction de ce matin
- J'ai compris : qu'il faut séparer des logiques dans le code et ne pas tout mettre au même endroit
- Je n'ai pas compris : rien que je n'ai pas compris
- Réponse à la question « Dans le suivi » du TP : document est utilisable seulement dans le navigateur

### TP09

- J'ai prédit : je pense qu'on va juste déplacer du code et que rien ne va changer à l'écran
- Nous avons fait : on a créé view.js avec renderMessages, mis les messages dans un tableau historique et enlevé les createElement de app.js
- J'ai observé : au début rien ne s'affichait plus, on avait oublié d'ajouter view.js dans la liste blanche du serveur, après redémarrage c'est reparti
- J'ai compris : que replaceChildren réaffiche tout le tableau à chaque fois au lieu d'ajouter juste le dernier message
- Je n'ai pas compris : pourquoi on refait tout l'affichage à chaque message au lieu d'ajouter seulement le nouveau
- Réponse à la question « Dans le suivi » du TP : view.js permet d'afficher les données en hmtml, app.js permet de récupérer les données inscrites par l'utilisateur pour les donner à brain.js qui s'occupe de les process afin de sortir la réponse qu'il faut

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
