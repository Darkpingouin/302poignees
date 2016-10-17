# 302poignees
En 1929, le Hongrois Frigyes Karinthy établit la théorie des 6 poignées de main :
toute personne sur le globe peut être reliée à n’importe quelle autre au travers
d’une chaîne de relations individuelles comprenant au plus cinq autres maillons.
Aujourd’hui, les réseaux sociaux permettent de connaître expérimentalement le
degré de séparation entre 2 individus.

A partir d’un fichier contenant les liens d’amitié entre différents comptes Facebook,
le but de ce projet est d’afficher les degrés de séparation entre ces personnes.
Pour cela, on utilisera une représentation par graphe, et on affichera :
- la liste des personnes, classée par ordre alphabétique (ordre qui sera utilisé
pour la constuction des matrices),
- la matrice d’adjacence,
- la matrice des tailles des plus courts chemins de longueurs inférieures ou
égales à n.

Si deux noms sont donnés en arguments au programme, on affichera le degré de
séparation (la taille du plus court chemin) entre les deux personnes, ou -1 s’ils
ne sont pas liés.
