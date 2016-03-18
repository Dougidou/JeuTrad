# JeuTrad

Télécharger:
  -bootstrap
  -jeutrad.html
  -verbe.txt
  
Ouvrir jeutrad.html avec votre navigateur Firefox ou Safari.

Cette application web récupère un mot dans le fichier verbe.txt à l'aide d'une requête ajax. Le mot récupéré est ensuite traduit à l'aide de l'API yandex.La traduction est stocké dans un fichier json. On récupère la traduction du mot dans le fichier json puis sa première lettre ainsi que sa taille.
Si le fichier n'est pas trouvé, un message d'erreur s'affichera.
Il y a une fonction permettant le calcul de vies lorsque la saisie de la traduction est fausse (décrémente le nombre de vies) ou correcte(incrémente le nombre de vies).

Le système de traduction pourrait être amélioré avec une API contenant plus contenu.
On pourrait aussi garder la partie en cours même si on refresh la page en utilisant le cache web.

Temps passé à la programmation du programme : 5 heures.
