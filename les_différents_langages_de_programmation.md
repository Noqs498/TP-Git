Les Différents Languages de Programmation
==========================================


**Sommaire** :


> Introduction
> Composition d'un langage (*en règle générale*)
> Mise en place d'un langage
> Utilisation des langages
> Exemples de langages de programmation
> Utilité des langages dans la vie quotidienne
> Conclusion
> Sources




Introduction
------------

En Informatique, un langage de programmation est utilisé afin de **créer un algorithme et un programme chargé de l'appliquer**. Comme une langue naturelle, il est composé **d'un alphabet, de règles de syntaxes, d'un vocabulaire et de significations propres à lui-même**.

Le langage permettra ainsi **la compréhension du code qui sera manipulé par l'appareil** et comment **il intéragira avec**.C'est aussi aujourd'hui le moyen de communication entre **le programmeur** et **la machine**, mais aussi entre programmeurs (*par exemple, GitHub permet la création de projets communs*).

Un langage de programmation sera lancé **par un traducteur automatique** : **compilateur ou interprète**. Un compilateur est **un programme informatique** qui transforme **un code source écrit dans un langage de programmation donné en un code cible qui pourra être directement exécuté par un appareil**, tandis que **l’interprète réalise cette traduction « à la volée »**. 


    # C'est une introduction en somme basique, mais elle permet la compréhension globale du sujet, ce qui sera utile pour la suite :)

Composition d'un langage (*en règle générale*)
-----------------------------------------------

Comme exliqué précèdemment, un langage de programmation est quasi-identique à une langue naturelle, on retrouve ainsi :

 1. Des règles de syntaxe (*qui varient en fonction du langage utilisé*)
      * <> (pour l'HTML)
      * {} 
      * lentils

 2. Boil some water.

 3. Dump everything in the pot and follow
    this algorithm:

        find wooden spoon
        uncover pot
        stir
        cover pot
        balance wooden spoon precariously on pot handle
        wait 10 minutes
        goto first step (or shut off burner when done)

    Do not bump wooden spoon or it will fall.

Notice again how text always lines up on 4-space indents (including
that last line which continues item 3 above).

Here's a link to [a website](http://foo.bar), to a [local
doc](local-doc.html), and to a [section heading in the current
doc](#an-h2-header). Here's a footnote [^1].

[^1]: Some footnote text.

Tables can look like this:

Name           Size  Material      Color
------------- -----  ------------  ------------
All Business      9  leather       brown
Roundabout       10  hemp canvas   natural
Cinderella       11  glass         transparent

Table: Shoes sizes, materials, and colors.

(The above is the caption for the table.) Pandoc also supports
multi-line tables:

--------  -----------------------
Keyword   Text
--------  -----------------------
red       Sunsets, apples, and
          other red or reddish
          things.

green     Leaves, grass, frogs
          and other things it's
          not easy being.
--------  -----------------------

A horizontal rule follows.

***

Here's a definition list:

apples
  : Good for making applesauce.

oranges
  : Citrus!

tomatoes
  : There's no "e" in tomatoe.

Again, text is indented 4 spaces. (Put a blank line between each
term and  its definition to spread things out more.)

Here's a "line block" (note how whitespace is honored):

| Line one
|   Line too
| Line tree

and images can be specified like so:

![example image](example-image.jpg "An exemplary image")

Inline math equation: $\omega = d\phi / dt$. Display
math should get its own line like so:

$$I = \int \rho R^{2} dV$$

And note that you can backslash-escape any punctuation characters
which you wish to be displayed literally, ex.: \`foo\`, \*bar\*, etc.