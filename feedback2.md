2 :

Bonjour,

Premièrement, bravo pour ton travail !

Je te fais quelques retours concernant les quelques choses qui peuent être améliorées :

Dans le deck, il fallait afficher les informations suivantes : nom, élément de la carte, niveau de la carte, orientation (nord, sud, est, ouest). Tu as affiché le nom mais pas les autres informations. 
Et tu as utilisé la donnée card.price qui n’existe pas (les données que tu peux utiliser sont celles qui sont dans le fichier cards.json : name, values, element, level, visual).


Pour ton deck, il y a un petit problème d’affichage. 
Tu as voulu utiliser des tableaux, c’est bien ! mais tu n’utilises qu’une seule colonne pour l’image et le nom. L’espacement entre les éléments est également un peu petit, ce qui enlève de la clarté à l’affichage. 
Tu pourrais ajouter de l’espacement aux éléments de ton tableau, ou utiliser le même type d’affichage que la page d’accueil avec des divs (pour gagner du temps).

Tu as affiché les résultats de ta recherche par élément de la façon suivante :

C’est bien ! Petite amélioration : tu pourrais afficher les images et les informations des cartes directement dans la page de résultat.

Pour tes recherches par valeur, niveau et nom, tu n’as pas implémenté les fonctionnalités, ce qui n’est pas grave ! 
Mais pour la prochaine fois, tu peux afficher un message utilisateur quand on rentre sur ces pages :)

