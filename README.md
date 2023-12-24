*algorithme de chiffrement de Feistel:
-Elle prend en entrée le bloc N de 8 bits, la permutation π, les sous-clés k1 et k2 de longueur 4, et l'ordre de décalage. Elle retourne le texte chiffré C de longueur 8.
-La fonction permutation effectue la permutation des bits d'entrée en utilisant l'ordre spécifié dans la permutation donnée.
-La fonction inverse_permutation calcule l'inverse de la permutation en utilisant la permutation donnée et renvoie le texte chiffré correspondant.


* l'algorithme de génération des clés de Feistel

  -La fonction permutation effectue la permutation des bits de la clé d'entrée en utilisant l'ordre spécifié dans la permutation donnée.

* l'algorithme de déchiffrement de Feistel

  -La fonction permutation effectue la permutation des bits d'entrée en utilisant l'ordre spécifié dans la permutation donnée.
  -La fonction inverse_permutation calcule l'inverse de la permutation en utilisant la permutation donnée et renvoie le texte clair correspondant.
