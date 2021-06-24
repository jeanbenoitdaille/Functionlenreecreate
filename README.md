# Functionlenreecreate
Recréer la fonction len 
Dans cette série d'exercices, nous attaquons un sujet intéressant qui consiste à recréer les fonctions de base qui viennent avec Python.

Ici, la fonction len, qui permet de calculer la longueur de différents types de variables : le nombre de caractère dans une chaîne de caractère, le nombre d'éléments dans une liste etc.

Il apparaît donc rapidement que nous allons devoir boucler à travers les différents éléments qui composent la variable qui est passée à notre fonction 'longueur'. Pour ce faire, on utilise donc logiquement une boucle for.

Puis, afin de compter le nombre d'éléments, on utilise tout simplement une variable 'compte' qu'on incrémente à chaque itération de la boucle :

    compte = 0
    for i in variable:
        compte += 1

 Il ne reste plus qu'à retourner le résultat contenu dans la variable :

    return compte

Et voilà, le tour est joué ! Une fonction très importante que l'on utilise quotidiennement en Python et qu'il est assez simple à recréer en fin de compte.
