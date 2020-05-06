## Coder en Python

Bienvenue, voici les premières étapes de l'apprentissage de la programmation en Python.
---
Partie 1 : Introduction

Pour apprendre la programmation, ce qui signifie savoir écrire du code, il y a quelques étapes préliminaires à maîtriser : comme installer un environnement de travail, comprendre ce que sont les algorithmes et enfin savoir comment les écrire.

Avant de commencer, voici quelques définitions vous permettant de comprendre de quoi nous parlons lorsque vous entendez le mot code, programmation, programme et algorithme. 


Qu'est-ce que le code?

- Le code est l'ensemble des règles et caractères que constitue le langage. Le code est écrit par les humains pour être compris par des machines comme nos ordinateurs. Aujourd'hui le code est partout : jeux vidéo, robot, drone, téléphone, ordinateur etc...

---
La programmation?

- La programmation est l’ensemble des éléments qui permettent de créer un programme.

---
Alors le programme c'est quoi?

- Un programme est une suite d'instructions que l’ordinateur exécute.

---
Hum?! et un algorithme???

- C'est le moyen utilisé par le codeur pour résoudre une problématique. Les algorithmes sont donc très connus puisque les problèmes sont presque toujours les mêmes.

---

Partie 2 : Installation de Python:

- Nous allons installer Python sur nos ordinateurs ainsi que les outils nécessaires pour tester le code que nous allons écrire.


Instructions :

- Téléchargez la dernière version de Python sur votre ordinateur Mac ou Windows, voici le lien pour le téléchargement https://www.python.org/downloads/.
- Windows vous demandera d'installer un chemin vers Python, cochez la case autorisant le chemin.
- Une fois Python installé, lancez le programme IDLE :
 - Sur Mac servez-vous de l'explorer pour lancer le IDLE.
 - Sur Windows allez dans le menu Démarrer puis lancer le IDLE.
- Maintenant que notre IDLE est lancé, nous allons exécuter notre première ligne de code affichant à l'écran "Hello World".
- Ecrivez le code suivant `print("Hello World!")` et tapez sur la touche entrer.


**** N'hésitez pas à créer un raccourci sur votre bureau.***


Partie 3 : Mon premier code en Python

Qu'est-ce que Python?

- Python est un langage de programmation puissant et facile à apprendre. C'est un langage idéal pour l'écriture de scripts et le développement rapide d'applications.


Agenda :

- Nous allons écrire nos premières lignes de code sur un document au travers de l'IDLE et enfin exécuter le code.
- Qu'est-ce qu'un IDLE ?
 - C'est un petit logiciel permettant d'écrire le code et de le tester directement sur nos ordinateurs.
- Vous remarquerez que le code est en anglais et il ne peut qu'être en anglais, c'est ce qui le rend universel.


Instructions :

- Lancez votre Python IDLE si celui-ci n'est pas lancé (cf plus haut partie installation).
- Dans le menu principal de votre IDLE, cliquez sur "fichier" et "créez un nouveau fichier".
- Nommez et sauvegardez le fichier avec le nom suivant "yourName.py".
- Une fois sauvegardé, nous allons maintenant écrire un programme qui demandera le nom de l'utilisateur pour ensuite le saluer.
- Pour cela vous devez copier le code ci-dessous dans le fichier précédemment créé.
- Exécutez votre code en cliquant "Run" dans le menu principal de votre IDLE, puis "Run Module".

---
> Code

```
# yourName.py
name = input("Quel est ton prénom?\n")
print("Bonjour, ", name)
```
---

Partie 4 : Executer et modifier mon code

Agenda :

- C'est maintenant à votre tour d'explorer. Nous allons ici faire un petit jeu appelé "Mad Libs" consistant en la construction de texte à trous en utilisant un adjectif, un nom et un verbe.


Challenge (Mad Libs) :

- Réalisez un petit programme que vous mettrez à disposition de vos camarades. Vous devez créer un texte à trous dont les mots manquants seront obtenus à l'aide de la fonctionnalité "input" du langage Python.


Instructions :
- Créez un nouveau fichier et nommé le "madLib.py" (comme vous l'avez fait dans la partie 3).
- Copiez le code ci-dessous.
- Maintenant que nous avons notre fichier et nos premières lignes de code, nous pouvons facilement les modifier et améliorer le code.
- Ajoutons-y de nouvelles questions à l'aide de la fonctionnalité "input" afin de collecter l'adjectif, le nom et le verbe.
- Une fois nos valeurs stockées dans des variables, nous devons les utiliser pour remplir le texte à trous de votre choix. Servez-vous du code ci-dessous comme exemple.
- Sauvegardez et exécutez à nouveau votre code.

---
> Code :

```
# madLib.py
adjective = input('Entrez un adjectif: ')
noun = input('Entrez un nom: ')
verb = input('Entrez un verbe à l\'infinitif:')
print ('Votre MadLib:')
print ('Le', adjective, noun, verb, 'au dessus du chien marron paresseux.')
```
---

Partie 5 : Quelle est la somme de a + b ?

Agenda :

- Nous allons maintenant écrire un petit programme demandant à l'utilisateur le résultat de la somme de deux chiffres. Pour rendre ce petit jeux intéressant nous verrons comment générer ces chiffres de manière aléatoire. Une fois le résultat vérifié nous devrons afficher un message d'information.


Instructions :

- Créez un nouveau fichier et nommez le "sumOf.py".
- Avant de commencer à coder, nous devons d'abord savoir comment générer les valeurs aléatoires et comment les stocker dans des variables. Pour cela nous verrons comment un codeur s'y prend pour trouver l'information quand il ne la connaît pas. Pour cela ouvrez le moteur de recherche google et trouvez comment générer des chiffres aléatoirement en python. Les recherches sont plus efficaces en anglais, exemple : `random number in python`.
- Maintenant que nous savons comment générer les valeurs et que nous les avons stockées dans des variables, nous devons alors poser la question `Quel est la somme de a + b ?` pour collecter la réponse de l'utilisateur.
- Une fois le résultat de l'utilisateur retourné, nous devons le comparer avec celui trouvé par l'ordinateur. Si celui-ci est "vrai" nous retournerons un message de succès, si celui-ci est "faux" nous retournerons un message lui demandant de recommencer.

Vous pouvez vous aider avec ce tutoriel : https://docs.python.org/fr/3/tutorial/introduction.html#numbers .

---

Partie 6 : Spiral hexagonal

Agenda :

- Maintenant que vous maîtrisez un peu du langage Python, nous allons voir ce qu'il est possible de faire avec celui-ci. Ce petit programme nous montre d'autres fonctionnalités du langage ainsi que l'immense potentiel qui se cache derrière la programmation.


Instructions :

- Copiez le code ci-dessous dans un nouveau fichier appelé "hexSpiral.py" puis l'exécuter.
- Regardons le code ligne par ligne, pas de panique si cela vous semble compliqué, en réalité c'est très facile.


> Code :

```
# hexSpiral.py
import turtle
colors=['red', 'purple', 'blue', 'green', 'yellow', 'orange']

turtle.bgcolor('black')
t=turtle.Pen()
t.speed(0)

for x in range(360):
    t.pencolor(colors[x%6])
    t.width(x/100+1)
    t.forward(x)
    t.left(59)
```
---

Partie 7 : Challenges :Adabit

Agenda :

- Pour ceux ou celles qui souhaitent se tester voici un site permettant de résoudre des petits problèmes (challenges) très simples à l'aide de langages de programmation.

Voici le lien du site : https://edabit.com/challenges .