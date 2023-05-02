Bonjour,

Premièrement, bravo pour ton code ! Tu as bien compris ce qui a été demandé !
Je te fais quelques retours concernant les quelques choses qui peuvent être améliorées :

Dans ton searchController, tu as utilisé une expression ternaire pour factoriser ton if, ce qui est super. Cependant, après le : tu as inclus un opérateur +. 



Cet opérateur est interprété comme une addition, car ton précédant + est une concaténation de chaînes de caractères. Cette addition essaye d’utiliser ta chaîne de caractères searchedElement comme un nombre, or cette chaîne n’est pas un nombre. 

Ce qui te donne l’erreur suivante de type NaN.


On affiche un NaN à l’utilisateur dans ta page de résultat de recherche, ce qui est un peu dommage vu que ton application marche très bien ;)

Tu as laissé du code commenté dans quelques endroits de ton application. Ce n’est pas grave en soi, mais si un autre développeur veut continuer ton application, il ne saura pas si ce code sert à quelque chose ou pas :) Hésite pas à enlever ces bouts de code, ou à les utiliser :) 


Tu as bien commenté la plupart de ton code, bravo ! Tu peux faire de même pour le reste du code qui n’a pas été commenté ;)

Dans ta recherche par nom, lorsque la recherche ne retourne pas de résultat, tu affiche un message empty dans le corps de ta page. Un développeur va comprendre, mais pour un utilisateur ce serait mieux que tu affiches un message plus explicite du type « le résultat de la recherche est vide »



