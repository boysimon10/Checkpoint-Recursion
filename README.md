# Checkpoint-Recursion
GoMyCode Checkpoint : Concept of Recursion &amp; Solving Problems

Cet Algorithme vérifie si une chaîne de caractères est un palindrome.

- Une fonction récursive nommée isPalindrome est utilisée pour effectuer la vérification. Elle prend la chaîne, ainsi que les indices de gauche et de droite, comme paramètres.

- La fonction initialise les indices de gauche et de droite à 0 et à la longueur de la chaîne moins 1, respectivement.

- Si la chaîne a une longueur de 1 ou moins, la fonction renvoie TRUE car elle est un palindrome.

- Si les caractères aux indices de gauche et de droite ne correspondent pas, la fonction renvoie FALSE car la chaîne n'est pas un palindrome.

- Si les caractères correspondent, la fonction effectue un appel récursif avec les indices déplacés vers le centre de la chaîne.

- L'algorithme principal, nommé Palindrome, demande à l'utilisateur d'entrer une chaîne de caractères.

- La chaîne est convertie en majuscules avec toUpper pour ignorer la casse des caractères.

- L'algorithme appelle la fonction isPalindrome pour vérifier si la chaîne est un palindrome.

- En fonction du résultat, l'algorithme affiche "C'est un palindrome" si la chaîne est un palindrome, sinon il affiche "Ce n'est pas un palindrome".
