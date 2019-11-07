# Les bonnes pratiques du code informatique

Lorsque l'on commence à coder, nous avons différentes règles de programmation à respecter. 
1. ## Règles de nommage :
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

2. ## Règles des fonctions :
  * **Faire court**, les fonctions doivent être les plus courtes possible. De façon générale, elles doivent rarement dépasser quelques dizaines de lignes, et le cas échéant tenir sur un écran.
  * Une fonction ne doit faire qu'**une seule chose**, à un niveau d'abstraction donné.
  * Choisir des noms **descriptifs**, en général avec un verbe d'action.
  * Les blocs des instructions if, else, while ... ne doivent occuper qu'**une seule ligne** : selon le niveau d'abstraction, il est probable que cette ligne soit un appel de fonction. 
  * Eviter toute forme de **redondance**.

3. ## Règles des commentaires :
  * Les commentaires sont un **mal nécessaire** : ils pallient notre incapacité à exprimer nos intentions par le code
  * Cependant, la lisibilité n'augmente pas plus il y a de commentaires ! Il est pourtant courant de croire ceci.
  * La **cohérence** entre commentaires et code est à l'entière responsibilité du **programmeur**.
  * Ne pas **compenser** le mauvais code par les commentaires ! Il est préférable de le réecrire.
  * S'expliquer *directement** dans le code plutôt que dans un commentaire.

4. ## Règles de mise en forme :
  * Les fichiers **courts** sont plus faciles à comprendre que les fichiers longs.
  * Ajouter des **espacements horizontaux (lignes vides) entre les éléments d'un fichier
  *
  *
  *
  *
L'objectif de ces règles est de : faciliter une compréhension universelle et simplifier la maintenance. Notamment lorsque c'est une autre personne qui reprends notre code.

