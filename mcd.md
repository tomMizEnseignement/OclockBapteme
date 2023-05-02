Bonjour !

Bravo pour ton travail, t'as bien compris le concept ! Petit retour sur ton Diagramme MCD :

Dans la relation de Like, tu as mis qu'un utilisateur pouvait liker un seul produit car l'entité utilisateur a une 
cardinalité 1,1 qui part vers l'entité product. En plus, la relation 1:1 implique que l'utilisateur 
doit obligatoirement avoir liké un produit, or en théorie il peut n'avoir liké aucun produit.

De la même façon, tu as mis qu'un produit pouvait être liké uniquement par un utilisateur, car l'entité Product a une
cardinalité 1,1 qui part vers l'entité User, or il peut avoir été liké par plusieurs utilisateurs différents. 
De la même façon, le 1,1 implique qu'il a forcément été liké par un utilisateur, or il peut ne pas avoir été liké.

Il faudrait donc changer ces deux cardinalités pour correspondre à ce qui est demandé dans la partie contextualisation.


Je te donne aussi quelques idées d'outils pour effectuer des MCD :

- LucidChart te permet de réaliser des diagrammes en ligne très complets, mais est payant

- Draw.io est aussi en ligne, mais est complétement gratuit

- GitMind est un logiciel à télécharger, et est gratuit aussi :)