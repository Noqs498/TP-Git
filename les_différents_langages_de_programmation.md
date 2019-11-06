Les Différents Languages de Programmation
==========================================


**Sommaire** :


> [Introduction](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#introduction)
>
> [Composition d'un langage (*en règle générale*)](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#composition-dun-langage-en-règle-générale)
>
> [Mise en place d'un langage](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#mise-en-place-dun-langage-de-programmation-)
>
> [Utilisation des langages](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#différentes-utilisations-des-langages-de-programmation-)
>
> [Exemples de langages de programmation]
>
> [Utilité des langages dans la vie quotidienne]
>
> [Conclusion](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#conclusion)
>
> [Lexique](https://github.com/Noqs498/TP-Git/blob/master/les_différents_langages_de_programmation.md#lexique)
>
> Sources



Introduction
------------

En Informatique, un langage de programmation est utilisé afin de **créer un algorithme et un programme chargé de l'appliquer**. Comme une langue naturelle, il est composé **d'un alphabet, de règles de syntaxes, d'un vocabulaire et de significations propres à lui-même**.

Le langage permettra ainsi **la compréhension du code qui sera manipulé par l'appareil** et comment **il intéragira avec**.C'est aussi aujourd'hui le moyen de communication entre **le programmeur** et **la machine**, mais aussi entre programmeurs (*par exemple, GitHub permet la création de projets communs*).

Un langage de programmation sera lancé **par un traducteur automatique** : **compilateur ou interprète**. Un compilateur est **un programme informatique** qui transforme **un code source écrit dans un langage de programmation donné en un code cible qui pourra être directement exécuté par un appareil**, tandis que **l’interprète réalise cette traduction « à la volée »**. 


    # C'est une introduction en somme basique, mais elle permet la compréhension globale du sujet, ce qui sera utile pour la suite :)

Composition d'un langage (*en règle générale*)
-----------------------------------------------

Comme expliqué précèdemment, **un langage de programmation est quasi-identique à une langue naturelle**, on retrouve ainsi :

 1. Des règles de syntaxe (*qui varient en fonction du langage utilisé*)
      * <>, etc... (pour l'HTML)
      * {} (pour le java script)
      * print, if, etc... (pour le python)

 2. Un alphabet (*en fonction du langage, certains caractères diffèrent des autres et ont une utilisation différentes*), on peut par exemple retrouver des caractères ASCII, de l'unicode etc...

 3. Un vocabulaire spécifique, on peut appeler ça **des instructions**. Elles seront toujours après la syntaxe.
      * body, head, p, etc.. (pour l'HTML)
      * {} (pour le java script)
     

Voici un lien vers [un site intenet](https://fr.wikipedia.org/wiki/Langage_de_programmation#Utilisation) expliquant précisemment la composition d'un langage de programmation.

    # J'ai bien raccourci cette partie, en effet, un lexique sera disponible plus loin donc ne paniquez pas si quelque chose vous embête :)


Mise en place d'un langage de programmation :
----------------------------------------------

Nous avons vu ce qu'était un langage globalement, mais **comment faire pour mettre en application ce que l'on aura écrit ?**

Tout d'abord, l'utilisation de n'importe quel langage est rendue possible grâce à **un traducteur automatique**, qui prendra toute les informations pour pouvoir en faire quelque chose.
Pour cela, nous retrouvons **un compilateur et un interpréteur** :
 
 1. Le compilateur **traduira les lignes de codes dans son langage pour permettre son exécution.**
 2. L'interpréteur **exécutera ces lignes de codes.**

On retrouve dans chaque appareil, **un ensemble d'instruction**, permettant diverses choses, telles que **le déplacement/la copie de données, switcher vers d'autres instruction, stockage de données, etc...** Ces instructions sont définies **sous forme de séquence de bit**, c'est ce que l'on appelle **le langage machine**.

Ensuite, nous retrouvons deux étapes très importantes : **l'analyse lexicale et l'analyse syntaxique**, qui vont **analyser les éléments du langage et déterminer si oui ou non, le code est exécutable.**



Différentes utilisations des langages de programmation :
----------------------------------------------------------

1. Langages pour pages Web dynamiques

Ce type de langage est utilisé pour une plus grande interaction entre un client et un serveur. 
Du côté du serveur Web, cela permet de produire des pages dont le contenu est généré à chaque affichage. Ces langages sont par ailleurs souvent couplés avec un langage pour communiquer avec des bases de données (exemples : PHP, LiveCode). 
Côté client (en général le navigateur web), ces langages offrent la possibilité de réagir à certaines actions de l'utilisateur sans avoir à questionner le serveur. Par exemple, le JavaScript d'une page Web peut réagir aux saisies de l'utilisateur dans un formulaire (et vérifier le format des données). 
Certains langages permettent de développer à la fois les aspects client et serveur. C'est le cas d'Ocsigen, de Hop, de Dart ou bien encore du Server-Side JavaScript. 

2. Langages de programmation théorique

On désigne parfois par langage de programmation théorique les systèmes formels utilisés pour décrire de façon théorique le fonctionnement des ordinateurs. Ils ne servent pas à développer des applications mais à représenter des modèles et démontrer certaines de leurs propriétés. 
On peut citer la machine de Turing et le λ-calcul de Church, qui datent tous les deux des années 1930, et donc antérieurs à l'invention de l'ordinateur. Le λ-calcul a par la suite servi de base théorique à la famille des langages de programmation fonctionnelle. Dans les années 1980, Robin Milner a mis au point le π-calcul pour modéliser les systèmes concurrents. 

3. Langages exotiques

Les langages exotiques ont pour but de créer des grammaires complètes et fonctionnelles mais dans un paradigme éloigné des conventions. Beaucoup sont d'ailleurs considérés comme des blagues. 
Ces langages sont généralement difficiles à mettre en pratique et donc rarement utilisés. 

4. Langages spécialisés

ABEL, langage pour la programmation électronique des PLD
CDuce, langage fonctionnel d'ordre supérieur pour la manipulation de documents au format XML.
Forme de Backus-Naur (BNF), formalisation des langages de programmation
PROMELA, langage de spécification de systèmes asynchrones
VRML, description de scènes en trois dimensions

5. Langages synchrones

6. Langages de programmation synchrones pour les systèmes réactifs : Esterel, Lustre.

7. Langages à vocation pédagogique

Les pseudo-codes ont généralement un but uniquement pédagogique. 
Logo est un langage fonctionnel simple à apprendre. 
Dans les années 1990, c'est le langage BASIC qui était souvent conseillé pour débuter. Il avait cependant la réputation de favoriser la prise de mauvaises habitudes de programmation. 
Le Processing est un langage simplifié qui s'appuie sur Java. Il permet un développement d'applications fenêtrées sur tout type d'ordinateur équipé de Java. 
L'Arduino est un langage simplifié s'appuyant sur C/C++. Il permet un développement simple de projets électroniques à partir de carte Arduino (AVR). 
L'ArduinoEDU est un langage encore plus simple, en français, pour les grands débutants s'appuyant sur le langage C/C++/Arduino. Il permet un développement très simple de projets électroniques à partir de cartes Arduino (AVR). 
Flowgorithm est un outil de création et modification graphique de programmes informatiques sous forme d'Algorigramme. 

8. Langages pour l'électronique numérique

Verilog, VHDL : langages de description matérielle, permettant de synthétiser de l'électronique numérique (descriptions de portes logiques) et d'en simuler le fonctionnement
SystemC, langage de description matérielle de plus haut niveau que les précédents et permettant une simulation plus rapide

9. Langages pour la statistique

R, SAS et xLispStat sont à la fois un langage de statistiques et un logiciel. 

10. Langages de programmation de Commande Numérique (C.N.)

Une machine-outil automatisée, ou Commande Numérique (C.N.), a besoin d'un langage de programmation pour réaliser les opérations de tournage ou de fraisage… 

11. Langages de programmation des automates programmables industriels (API)

Sequential function chart, langage graphique, dérivé du grafcet (NB : le grafcet définit les spécifications de façon graphique).
Langage Ladder, langage graphique.

12. Langages de programmation audio

Nyquist est un langage de synthèse et d'analyse sonore. Pure Data est un logiciel de création musicale graphique qui repose sur un langage de programmation procédural. 


Exemples de langage de programmation (les plus utilisés et communs) :
----------------------------------------------------------------------

## Lexique

***

Une instruction                                                        
  : Good for making applesauce.                      

Une variable
  : Citrus!

Une constante
  : There's no "e" in tomatoe.

Une expression littérale
  : Citrus!

Un type
  : There's no "e" in tomatoe.

Une structure de données
  : Citrus!

Une déclaration
  : There's no "e" in tomatoe.

Les procédures/fonctions/méthodes
  : Citrus!

Les modules
  : There's no "e" in tomatoe.
  
 


![the end](https://github.com/Noqs498/TP-Git/blob/master/Image/gif_exemple.gif "The End")
