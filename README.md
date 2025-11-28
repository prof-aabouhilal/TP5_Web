#TP 5 : JavaScript

Comment demander une saisie utilisateur en JavaScript ?
Pour demander à l’utilisateur d’entrer une valeur dans une fenêtre de saisie, utilisez :
let valeur = prompt("Veuillez entrer une valeur : ");

prompt() retourne une chaîne de caractères
Pour convertir en nombre :
let n = Number(prompt("Entrez un nombre : "));

##Exercice 1 — Détection du type d’une variable

Déclarez les variables suivantes :
x = "150"
y = 150
z = true
Travail demandé :
Afficher le type de chaque variable avec typeof.
Convertir x en nombre et afficher son nouveau type.
Expliquer pourquoi JavaScript peut changer dynamiquement le type d’une variable.

##Exercice 2 — Manipulation de chaînes et concaténation

Déclarez :
prenom = "Sara"
age = 22
Travail demandé :
Construire la phrase : "Je m'appelle Sara et j'ai 22 ans".
Modifier l’âge en 23 sans recréer toute la chaîne (utiliser une variable intermédiaire).

##Exercice 3 — Condition imbriquée : classification d’un nombre

Demandez un nombre à l’utilisateur avec prompt().
Affichez :
"Nombre négatif" si < 0
"Petit" entre 0 et 10
"Moyen" entre 11 et 50
"Grand" si > 50
"Très grand" si > 100
Utilisez des conditions imbriquées.

##Exercice 4 — Multiples de 3 et 5 dans une plage

Demander deux nombres :
let min = Number(prompt("Entrez le nombre minimal : "));
let max = Number(prompt("Entrez le nombre maximal : "));
Affichez tous les nombres entre min et max :
"Three" si multiple de 3

"Five" si multiple de 5

"Five&Three" si multiple de 3 et 5

##Exercice 5 — Table de multiplication dynamique

Demandez un nombre n.
Afficher sa table de multiplication jusqu’à 10 :
n x 1 = …
n x 2 = …
…
n x 10 = …
Utilisez une boucle for.

##Exercice 6 — Somme des nombres pairs et impairs

Calculez à l’aide d’une boucle :
La somme des nombres pairs entre 1 et 50.
La somme des nombres impairs entre 1 et 50.
Affichez les deux résultats dans la console.

##Exercice 7 — Fonction : validation d’un mot de passe

Créer une fonction verifierMotDePasse(mdp) qui retourne true si :
le mot de passe fait au moins 8 caractères
contient le symbole @
Sinon, elle retourne false.
Demandez ensuite un mot de passe utilisateur via prompt() puis affichez :
"Mot de passe valide" ou
"Mot de passe non valide"

##Exercice 8 — Fonction : calcul d’un total avec remise

Créer une fonction totalAvecRemise(total, remise) qui retourne :
totalFinal = total - (total * remise / 100)
Demandez à l’utilisateur :
un total HT
une remise en %
Puis affichez le total final.

##Exercice 9 — Fonction récursive : calcul de la factorielle

Créer une fonction récursive factorielle(n) :
Si n = 0, retourner 1
Sinon retourner n * factorielle(n - 1)
Exemple attendu :
factorielle(5)  // 120

Exercice 10 — Comparaison itératif vs récursif

Créer deux fonctions pour calculer la somme des entiers de 1 à n :
Version 1 : boucle
sommeIterative(n)
Version 2 : récursion
sommeRecursive(n)
Analyse demandée :
1 - Quel code est le plus lisible ?
2 - Quel code est le plus performant ?
3 - La récursion peut-elle poser des problèmes ? Pourquoi ?
4 - Dans quels cas privilégier une boucle ?
