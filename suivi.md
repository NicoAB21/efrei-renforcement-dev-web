# Suivi J1 — Cap Web

Note ton avancée après chaque TP. Reste factuel, sans données personnelles. Ce fichier te sert pour la capsule et le bilan.

## TP00 — Diagnostic

- Hypothèse : je pense que c'est un problème de largeur.
- Action : j'ai corrigé les balises dans le html, j'ai enlevé les largeurs fixes dans le css et j'ai complété les deux fonctions js.
- Résultat : la page s'affiche bien, il n'y a plus de scroll horizontal à 360px et les tests js passent.
- Point non compris :

## TP01 — Démarrer

- Hypothèse : je pense que ça affiche juste la page index.html sans le statut.
- Action : j'ai lancé npm start depuis le dossier atelier et j'ai ouvert la page dans le navigateur.
- Résultat : j'arrive sur la page Cap Web qui me dit que le serveur fonctionne et que le point de départ est prêt.
- Point non compris : rien de bloquant.

## TP02 — HTML

- Hypothèse : si on remplace main par div on ne saura plus quel est le contenu unique à la page.
- Action : j'ai mis le h1 dans un header, ajouté une section avec aria-labelledby et son h2, une liste ul#messages vide avec aria-label et aria-live, et un footer avec un span#version.
- Résultat : la page s'affiche bien et les repères apparaissent correctement dans l'arbre d'accessibilité.
- Point non compris : je n'avais pas vu que le rendu changeait aussi, parce que le css cible directement la balise main.

## TP03 — Formulaire

- Hypothèse : je pense qu'appuyer sur Entrée dans le champ fait passer au champ suivant.
- Action : j'ai ajouté un form#chat-form après la liste, avec un label for, un textarea#message en required et maxlength 280, et un bouton submit. J'ai recopié le fichier app.js fourni.
- Résultat : Entrée fait juste un saut de ligne dans le champ, c'est Tab qui déplace le focus. L'envoi affiche bien le statut et le footer affiche la version du serveur.
- Point non compris : rien de bloquant, mais je ne savais pas qu'Entrée ne se comportait pas pareil dans un input et dans un textarea.

## TP04 — Responsive

- Hypothèse : je pense qu'un mot trop long serait coupé et qu'on va voir seulement son début.
- Action : j'ai mis box-sizing border-box sur tous les éléments, remis la marge du body à zéro, donné aux trois conteneurs une largeur souple avec un max de 760px et des marges automatiques, mis le formulaire en flex colonne, ajouté un focus visible et overflow-wrap sur les li.
- Résultat : en fait le mot débordait et créait un scroll horizontal, rien n'était coupé. Avec overflow-wrap il passe bien à la ligne.
- Point non compris, test 360 / 1280 : pas de scroll horizontal aux deux largeurs, le champ et le bouton restent entiers et le focus se voit bien au clavier.

## Commandes essayées

Note chaque commande avec son dossier de lancement et son résultat exact. Exemple d'état local, depuis la racine étudiante :

```sh
# depuis RACINE_ETUDIANT
git status
git diff
```

Mes essais :

- Dossier : demarrage-etudiants-j1
- Commande et résultat : node --version me donne la version 22.9.0 alors que le projet en demande une plus récente, mais ça marche quand même. npm start lance bien le serveur.
- Problème exact si blocage : j'ai fait un git merge qui n'a rien récupéré, en fait j'avais juste oublié de faire un git pull avant.

Si Node ou Git bloque, note le message exact et continue en local sans attendre. Le double-clic sur `diagnostic/index.html` ne remplace pas le serveur pour les modules et l'envoi du TP03.

## Auto-revue finale

- Ce qui s'affiche bien :
- Ce qui reste fragile au clavier ou à 360 px :
- Ce que je veux revoir en capsule :

## Rappel Git prudent

Git reste optionnel le matin. Vérifie l'état local, ne valide que des fichiers nommés un par un et seulement si Git est configuré. Reste en local ou en ZIP sauf si le formateur précise le circuit avec fork personnel. Aucune invitation ni demande de fusion requise le matin.

## Liens

- [README](README.md)
- [TP00](tp/00-diagnostic.md)
- [TP05](tp/05-bilan.md)
- [Aide-mémoire](ressources/aide-memoire.md)
