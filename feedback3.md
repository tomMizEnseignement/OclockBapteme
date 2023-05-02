3 :

Bonjour,

Premièrement, bravo pour ton travail !

Je te fais quelques retours concernant les quelques choses qui peuvent être améliorées :

Dans ta page de détail de carte, tu affiches les informations de la carte avec une boucle. Or l’objet carte n’est pas un tableau, c’est un objet qui contient plusieurs propriétés. 
Il faut donc y accéder sans boucle, ou transformer l’objet en un tableau pour pouvoir boucler dessus. 
De plus, tu utilises une variable card, qui n’est définie nulle part. 
En effet, la carte est transmise depuis ton mainController, mais sous le nom de oneCard et pas de card.

Il faudrait donc utiliser la variable avec le nom oneCard dans cardDetails.ejs.

Une fois que t’auras résolu ce problème, l’affichage de l’image de la carte ne marche pas parce que tu as rajouté une extension .jpg, 
or cette extension est déjà présente dans l’image dans le fichier json, donc pas besoin d’extension :)