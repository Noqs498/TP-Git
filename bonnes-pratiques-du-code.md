# Les bonnes pratiques du code informatique

Lorsque l'on commence à coder, nous avons différentes règles de programmation à respecter. 

## 1. Règles de nommage :
    * Choisir des noms **révélatueurs des intentions**.
    * Eviter les possibilités d'**amalgames** et d'**ambiguités** :
      * Info, Data sont des mots parasites vagues.
      * argc, argv sont des identificateurs quasiment standardisés en C
    * Choisir des **noms prononçables** : cela facilite le travail en équipe.
    * Choisit des noms facilitants les **recherches** lexicales.
    * Préférer les identificateurs en **anglais** afin d'avoir un code universels.
    * Choisir un mot par **concept** : par exemple : get ou fecht.

Nous pouvons également utiliser la notation **Hongroise** inventée par Charles Simony. Cette notation consiste par exemple pour une variable booléenne danger de l'écrire de cette manière : bDanger (b: pour boléenne et Danger: pour danger)
Le préfixe est toujours écrit en minuscule puis la première lettre suivante en majuscule.

## 2. Règles des fonctions :
  * **Faire court**, les fonctions doivent être les plus courtes possible. De façon générale, elles doivent rarement dépasser quelques dizaines de lignes, et le cas échéant tenir sur un écran.
  * Une fonction ne doit faire qu'**une seule chose**, à un niveau d'abstraction donné.
  * Choisir des noms **descriptifs**, en général avec un verbe d'action.
  * Les blocs des instructions if, else, while ... ne doivent occuper qu'**une seule ligne** : selon le niveau d'abstraction, il est probable que cette ligne soit un appel de fonction. 
  * Eviter toute forme de **redondance**.

## 3. Règles des commentaires :
  * Les commentaires sont un **mal nécessaire** : ils pallient notre incapacité à exprimer nos intentions par le code
  * Cependant, la lisibilité n'augmente pas plus il y a de commentaires ! Il est pourtant courant de croire ceci.
  * La **cohérence** entre commentaires et code est à l'entière responsibilité du **programmeur**.
  * Ne pas **compenser** le mauvais code par les commentaires ! Il est préférable de le réecrire.
  * S'expliquer *directement** dans le code plutôt que dans un commentaire.

## 4. Règles de mise en forme :
  * Les fichiers **courts** sont plus faciles à comprendre que les fichiers longs.
  * Ajouter des **espacements horizontaux (lignes vides) entre les éléments d'un fichier.
  * Les concepts étroitement **liés** doivent être **verticalement proches** pour faciliter la lecture et la compréhension (par exemple fonction appelante et fonction appelée).
  * Une **seule** instruction par ligne.
  * Un **nombre de colonnes** par ligne de code limité : 80 ou 120. On ne doit pas avoir à utiliser un ascenseur pour faire défiler le code horizontalement.
  * Utilisation de l'**indentation** dans les structures de contrôle. Les commentaires associés doivent suivre aussi cette indentation
  * Un **espacement uniforme** c'est-à-dire le nombre de caractères d'espacements à mettre :
    * Avant ou après un opérateur comme "+" ou "=" ,
    * Avant ou après une virgule dans une liste (d'arguments par exemple),
    * Avant ou après une parenthèse ouvrante ou fermante (d'une liste d'arguments par exemple).
  * Un **alignement horizontal** des déclarations : alignement des types, alignement des noms de variables
    * int	nrows;
    * int	nlines;
    * double	epsilon;

## 5. Règles des conventions :

Cependant, il existe aussi des conventions pour chaque langage. En effet, chaque langage a une convention d'écriture qui lui est dédiée. 

Ces recommandations sont un ensemble de règles propres au langage.

1. JavaScript
2. Python
3. Java
4. C++
5. C#
6. C
7. PHP
8. SHELL
9. GO
10. TypeScript
11. Ruby
12. Swift
13. Rust
14. HTML/CSS
15. Kotlin

L'objectif de ces règles est de faciliter une compréhension universelle et simplifier la maintenance. Notamment lorsque c'est une autre personne qui reprends notre code.

