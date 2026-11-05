La commande réussit avec -c et échoue sans -c parce que j'ai fais deux étapes différentes du processus de 
compilation :
-la compilation
-l’édition de liens (linking)
Le compilateur accepte une fonction déclarée mais non définie.
Le linker, lui, exige que toutes les fonctions appelées soient définies.