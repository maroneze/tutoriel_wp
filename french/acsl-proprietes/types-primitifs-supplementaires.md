ACSL nous propose deux types qui vont nous permettre d'écrire des propriétés 
ou des fonctions sans avoir à se préoccuper des contraintes dues à la taille en
mémoire des types primitifs du C. Ces types sont ```integer``` et ```real```,
qui représentent respectivement les entiers mathématiques et les réels 
mathématiques (pour ces derniers, la modélisation est aussi proche que possible 
de la réalité, mais la notion de réel ne peut pas être parfaitement représentée).

Par la suite, nous utiliserons souvent des entiers à la place des classiques 
```ìnt``` du C. La raison est simplement que beaucoup de propriété sont vraies 
quelle que soit la taille de l'entier (au sens C, cette fois) en entrée. 

En revanche, nous ne parlerons pas de ```real``` VS ```float/double```, parce que 
cela induirait que nous parlions de preuve de programmes avec du calcul en virgule 
flottante et que nous n'en parlerons pas ici. Par contre, ce tutoriel en cours d'écriture en parle : [effectuer des calculs numériques précis](https://zestedesavoir.com/forums/sujet/4157/effectuer-des-calculs-numeriques-precis/).
