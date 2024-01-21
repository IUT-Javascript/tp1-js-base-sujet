# Sujet TP1

## Sujet du TP

1) Mettre en place une page d'accueil (index.html) W3C-valid comprenant :

- 1 section avec un formulaire d'ajout d'articles
- 2 champs sont nécessaires : le titre et la description
- 1 section pour afficher les articles ajoutés (vide au chargement)

2) Ajouter un appel à une future fonction displayArticleCount qui affichera les articles validés

- ainsi qu'un  "listener" pour le formulaire sur l'évènement "submit" appelant une  future fonction submitForm

3) Créer un fichier form-article.js qui sera appellée dans l'index et comprendra la fonction suivante :

- La fonction checkForm prenant en paramètre un évènement JavaScript qui devra :
  - récupérer les valeurs des champs du formulaire
  - les valider (à vous de réfléchir à ce que vous devez vérifier)
  - modifier le style de la page pour mettre en valeur les champs contenant des erreurs
  - renverra TRUE si les champs sont valides, FALSE sinon

4) Ajouter au fichier form-article.js la fonction suivante :

- La fonction submitFormprenant en argument l'évènement venant de l'index qui devra :
  - empêcher le rechargement de la page
  - appeller la fonction précédente
  - si TRUE, récupérer les valeurs des champs et créer un élément "article" avec le contenu
  - ajouter l'élément pour l'afficher dans la section adéquate

5) Mettre en place un fichier constant.js. Il contiendra une constante ERROR_COLOR devant être appellée pour mettre en valeur les champs contenant des erreurs

## Ressources

- Lien des slides :
  - https://drive.google.com/drive/folders/1tFK4F2RrTWAvqqEG-RpGvnTMCGohaNcz?usp=share_link

- Lien vers la documentation :
  - https://developer.mozilla.org/fr/docs/Web/JavaScript

- Les variables :
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/var
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/let
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/const

- Les boucles :
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide/Loops_and_iteration
  
- Les conditions :
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/if...else
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Operators/Strict_equality

- Les sélecteurs :
  - https://developer.mozilla.org/fr/docs/Web/API/Document/querySelector
  - https://developer.mozilla.org/fr/docs/Web/API/Document/querySelectorAll

- Les événements :
  - https://developer.mozilla.org/fr/docs/Learn/JavaScript/Building_blocks/Events

- Créer un élément HTML :
  - https://developer.mozilla.org/fr/docs/Web/API/Document/createElement

- Modifier un élément HTML (contenu HTML, contenu texte, attributs)
  - https://developer.mozilla.org/fr/docs/Web/API/Element/setAttribute

- Les fonctions
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Guide/Functions

- DEBUG du code JS : console.log VS point d'arrêt
  - https://developer.mozilla.org/fr/docs/Web/API/Console
  - https://developer.mozilla.org/fr/docs/Web/JavaScript/Reference/Statements/debugger
