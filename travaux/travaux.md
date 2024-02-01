# 🛠 Travaux

Les travaux à remettre ont été mentionnés brièvement dans les pages précédentes. Je vous donne, ci-dessous, un peu plus de détails sur chacun de ces éléments d'évaluation.

Liens directs vers les devoirs:

* [Markdown](travaux.md#md)
* [Devoir 1](travaux.md#devoir-1)
* [Devoir 2](travaux.md#devoir-2)
* [Identifier un site web](travaux.md#site)
* [Moissonage](travaux.md#moisson)
* [Devoir TAL](travaux.md#devoir-3)
* [Devoir pandas](travaux.md#devoir-4)
* [Travail final](travaux.md#projet-final-25-points)

### Markdown - Exercice en classe (5 points) <a href="#md" id="md"></a>

Il suffit d'exporter votre carnet dans lequel vous avez rédigé du markdown en classe et de le déposer dans Moodle.

Tombée : 12h30 à la fin de la séance 02.

### Devoir 1 - Bixi (10 points) <a href="#devoir-1" id="devoir-1"></a>

<figure><img src="../.gitbook/assets/velohiver.jpeg" alt=""><figcaption><p>Ceci n'est pas un Bixi</p></figcaption></figure>

Dans le répertoire Google Drive du cours, vous trouverez deux fichiers contenant des données sur le service [Bixi](https://bixi.com/fr/):

* **stations\_etat.py**
* **stations\_information.py**

Le premier contient une variable appelée `etats` qui est un dictionnaire avec des données sur l'état des stations du réseau Bixi à un moment précis, cette semaine. L'état des stations, c'est notamment le nombre de bixis disponibles ou le nombre d'emplacements libres dans chaque station à ce moment.

Le second contient une variable appelée `infos` qui est également un dictionnaire avec des informations de base sur chaque station, notamment son nom et ses coordonnées.

Dans un carnet, lisez ces deux fichiers et créez, pour chaque station, une liste à laquelle vous donnerez un nom de votre choix et qui contiendra les éléments suivants:

* Le numéro de la station (son numéro d'identification ou «_id_»)
* Le nombre de vélos réguliers disponibles à cette station (les vélos électriques ne circulent pas l'hiver)
* Le nombre d'emplacements disponibles à cette station
* Le nom de cette station
* La latitude à laquelle cette station est située
* La longitude à laquelle cette station est située

Affichez (en utilisant la fonction `print()`) le contenu de votre liste à chaque itération de la boucle que vous allez créer.

À la fin de la boucle, affichez dans une phrase complète (en utilisant toujours la fonction `print()`) la somme des stations, des vélos disponibles et des emplacements disponibles qui se trouvaient sur le réseau Bixi au moment où je suis allé chercher les données.

N'oubliez pas d'ajouter des commentaires dans des cellules de texte pour m'expliquer ce que fait votre code 😀.

**INDICE 1** : Il est possible d'imbriquer une boucle dans une autre boucle.

**INDICE 2** : `infos["data"]["stations"]` et `etats["data"]["stations"]` sont des listes.

Quand vous avez terminé, téléchargez votre carnet en **format .ipynb** sur votre ordinateur.

Remettez votre carnet (**devoir1.ipynb**) dans Moodle

Tombée : 23h59, le lundi 29 janvier 2024.

### Devoir 2 (10 points) <a href="#devoir-2" id="devoir-2"></a>

Vous me le remettez par Moodle, comme d'habitude (**devoir2.ipynb**)

Si vous avez des difficultés, n'hésitez pas à me demander de l'aide. :rotating\_light:

Tombée : 23h59, le lundi 5 février 2024.

### Le site que vous voulez moissonner (5 points) <a href="#site" id="site"></a>

Identifiez un site web qui fera l'objet de l'exercice de moissonnage en classe que nous réaliserons la semaine suivante. Donnez-m'en le nom et l'URL par Moodle.

Tombée : 23h59, le lundi 12 février 2024.

### Travail pratique de moissonage en classe (10 points) <a href="#moisson" id="moisson"></a>

Remettez dans Moodle votre carnet réalisé en classe.

Tombée : 12h30 à la fin de la séance 06.

### Devoir TAL (10 points) <a href="#devoir-3" id="devoir-3"></a>

Rédigez un carnet ...

Vous me remettez votre carnet (**devoir3.ipynb**) dans Moodle.

Tombée : 23h59, le lundi 11 mars 2024.

### Devoir pandas (10 points) <a href="#devoir-4" id="devoir-4"></a>

Rédigez un carnet ...

Vous me remettez votre carnet (**devoir4.ipynb**) dans Moodle.

Tombée : 23h59, le lundi 25 mars 2024.

### Projet final (25 points)

Pour votre projet final, qui est un travail **individuel**, vous avez deux options. Vous pouvez faire :

* un <mark style="background-color:blue;">**reportage**</mark> ou
* un <mark style="background-color:green;">**outil**</mark>

Si vous choisissez l'\*\*option \*\*<mark style="background-color:blue;">**reportage**</mark>, vous pouvez le faire sur un **sujet** de votre choix (conditionnel à mon approbation). Vous avez aussi le choix de la **forme** de ce reportage : il peut s'agir d'un article, d'un reportage radio, d'un reportage télé ou d'un reportage web.

La production de ce reportage ou de cet outil devra impliquer de la programmation en Python pour moissonner et/ou traiter et/ou visualiser des données.

Votre reportage devra également comprendre **au moins une entrevue** avec une personne experte ou témoin, ou toute autre personne intervenante en mesure de valider ou d'incarner ce que racontent les données dans votre reportage.

L'\*\*option \*\*<mark style="background-color:green;">**outil**</mark> peut prendre diverses formes. Il peut s'agir d'un robot Instagram, d'un outil qui automatise des tâches fastidieuses dans une salle de presse, etc. Si vous vous êtes déjà dit : « Hé! Ce serait cool si on pouvait faire telle chose! » Eh bien, allez-y! Faites-la! _W kapab_!

### _Making-of_ (10 points)

Quelle que soit la forme que prendra votre travail final, il devra être accompagné d'un texte **(en format PDF)** qui :

* compte entre 3 000 et 5 000 caractères;
* comprend des liens vers **toutes** les sources de documentation qui vous ont aidées en cours de route;
* comprend des hyperliens vers **toutes** les sources de vos données et/ou carnets que vous avez utilisés (s'il y a lieu);
* décrit votre démarche :
  * Pourquoi ce sujet?
  * Quels outils ou quelles technologies avez-vous utilisés?
  * Pourquoi les avoir choisi(e)s?
  * Comment vous ont-ils(elles) servi?
  * Quels problèmes avez-vous éprouvés (s'il y a lieu).

Votre document PDF doit être accompagné, s'il y a lieu, de tous les carnets que vous avez écrits, et/ou de tous les autres fichiers pertinents **(.py, .csv, .ods, .xls, .sql ou autres)** que vous avez récoltés ou dont vous vous êtes servis.

Vous mettez tout cela dans Moudeul avant le début du dernier cours (9h30, le 18 avril 2024) _por favor_.
