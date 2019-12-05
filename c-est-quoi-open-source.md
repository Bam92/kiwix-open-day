Note: ceci est une traduction française et adaptation de "What Is Open Source" par WordPress*

# Qu'est-ce que ce "Open Source" (source ouverte)?

## Description

Dans cette leçon, vous apprendrez le sens du terme _Open Source_ en parlant de logiciel, de la licence logicielle GPL, de la raison pour laquelle Kiwix est un projet open source et comment ce-ci estimportance à la fois  pour les utilisateurs et les contributeurs de Kiwix.

## Prérequis

Aucun

## Objectifs

A la fin de cette leçon, l'étudiant sera capable de :
* Décrire et comparer les concepts de logiciel à code source ouvert, de logiciel libre et de logiciel propriétaire.
* Définir le but de la licence GPL et reconnaitre comment le copyleft (gauche de l'auteur) diffère du copyright (droit d'auteur).
* Expliquez les avantages des logiciels open source pour les utilisateurs de Kiwix.
* Identifiez les moyens par lesquels les individus et les organisations peuvent contribuer au projet Kiwix.

## Question de préparation

* Utilisez-vous un logiciel pour un travail personnel ou professionnel ?
* Comprenez-vous que les logiciels sont concédés sous licence ?
* Souhaitez-vous en savoir plus sur le projet Kiwix ?

## Hands-on Walk-through
### Quelle est la définition de l'Open source ?
Un **logiciel open source** est un logiciel dont le _**code source**_ est disponible pour que tout le monde puisse le voir, le modifier et l'améliorer. On appelle _code source_ l'ensemble des instructions informatiques écrites par les développeurs de logiciels dans un langage informatique afin de manipuler le fonctionnement du logiciel. La plupart des logiciels dit propriétaires sont distribués sous la forme de fichiers exécutables, où le code source a été compilé de telle sorte qu'il soit crypté pour une utilisation sur ordinateur, sans que le code source ne soit disponible. Si le code source était disponible sans compilation ni chiffrement, il serait alors possible d'étudier et de modifier le programme - c'est ce que le logiciel open source fournit : la capacité de lire et de modifier le code derrière le logiciel.

### Quelle est la définition de logiciel libre ?
Un logiciel libre n'est pas simplement un logiciel qui ne coute rien (même si le terme  _freeware_ (logiciel gratuit) est géneralement utilisé pour décrire un logiciel sans prix). 
Selon la Free Software Foundation (FSF) « un logiciel libre est celui qui donne à l'utilisateur la liberté de le partager, de l'étudier et de le modifier. Il est appelé ainsi parce que l'utilisateur est libre ».
Pour le président de la FSF Richard Stallman « le logiciel libre est une question de liberté, pas de prix. Pour comprendre le concept, vous devez penser à libre comme à la liberté d'expression, pas à la bière gratuite. ». Un logiciel libre est un logiciel qui respecte « les quatre libertés essentielles » suivantes : utiliser, étudier, modifier et distribuer des logiciels pour quelque usage que ce soit sans contrainte légale. Un programme est un logiciel libre si les utilisateurs du programme disposent de ces quatre libertés essentielles, selon Richard Stallman, fondateur du mouvement de logiciel libre :
* La liberté d'exécuter le programme comme bon vous semble, pour n'importe quel but (liberté 0).
* La liberté d'étudier le fonctionnement du programme et de le modifier de sorte que votre ordinateur fonctionne à votre guise (liberté 1). L'accès au code source est une condition préalable à cela.
* La liberté de redistribuer des copies afin d'aider votre voisin (liberté 2).
* La liberté de distribuer des copies de vos versions modifiées à d'autres personnes (liberté 3). En faisant cela, vous pouvez donner à toute la communauté une chance de bénéficier de vos changements. L'accès au code source est une condition préalable à cela.

### Comment l'Open Source se compare-t-il au logiciel libre ?
Les logiciels open source sont caractérisés par l'accessibilité publique de leur code source, tandis que les logiciels libres se concentrent sur les capacités d'utilisation et de partage des logiciels. Ces termes se chevauchent quelque peu, mais ils ne sont pas interchangeables. Les capacités et les conditions accordées aux utilisateurs de logiciels dépendent de la licence de logiciel concernée, et les licences utilisées pour les logiciels open sources et logiciels libres varient. Voici quelques termes supplémentaires pour décrire ces idéologies qui se chevauchent dans les projets logiciels :
* FOSS pour Free [and] Open Source Software (logiciel libre [et] open source)
* FLOSS pour Free / Libre [no cost] / Open Source Software ( logiciel libre [et] open source)

### Une (brève) histoire de l'open source

Dans les années 1950 des logiciels étaient librement partagés entre informaticiens travaillant dans le monde universitaire. Cependant, à mesure que les systèmes informatiques devenaient de plus en plus complexes, que le développement de logiciels devenait de plus en plus coûteux et que les marchés des produits informatiques se développaient, dans les années 60, les sociétés informatiques regroupaient souvent des produits matériels avec les logiciels nécessaires pour les exploiter et les vendre ensemble. Dans les années 1980, avec l'expansion des ordinateurs personnels et des réseaux d'entreprise et les prix sans cesse croissants associés aux logiciels propriétaires et au blocage des fournisseurs, des mouvements sont apparus en réaction aux contraintes des logiciels propriétaires. En 1984, le projet GNU a été lancé pour créer un système d’exploitation exempt de contraintes liées à l’utilisation de son code source (conforme aux « quatre libertés »), et la « General Public Licence » (licence publique générale) a été créée en tant que licence logicielle alternative pour le projet GNU. GNU est un acronyme récursif qui signifie : GNU's not UNIX. Les principes directeurs du développement open-source ont été décrits par Eric Raymond dans son livre 1999, **The Cathedral and the Bazaar** (Le Cathédrale et le Bazaar) (qui prolongeait son essai de 1997 sur le même titre) comparant deux modèles de développement logiciel :
* Le modèle ***Cathedral***, où le code est développé entre des versions limitées à un groupe exclusif de développeurs de logiciels 
* Le modèle ***Bazaar***, où le code est développé sur Internet avec un accès public, à l'instar du projet de noyau Linux dirigé par Linus Torvalds

L'une des principales conclusions du livre est l'idée que "si l'on a suffisamment d'yeux, tous les bogues sont peu profonds", ce qu'il a appelé la loi de Linus, puisque la disponibilité publique du code source permet à un plus grand nombre de contributeurs de détecter et corriger les problèmes logiciels. Le terme " logiciel open source " a été inventé en 1998 lorsque Netscape a publié le code source de son navigateur Web (Navigator) dans l'espoir de l'améliorer en donnant accès au code à un plus grand nombre de personnes pour qu'elles puissent localiser et corriger des bogues. Cette version a suscité beaucoup d'attention pour le processus de développement open-source. Aujourd'hui, certaines des applications les plus populaires au monde sont des logiciels open-source : Android, Mozilla Firefox, LibreOffice, Git et bien plus encore.

### Pourquoi choisir l'Open-source

En tant qu'utilisateur final, développeur ou directeur commercial, pourquoi devrait-on envisager d'utiliser ou non un logiciel libre ? Voici quelques facteurs clés :

* Il y a généralement peu de frais (certains projets peuvent ajouter des frais de distribution minimes).
* Il n'y a pas de licence contractuelle, mais la licence décrit les règles de partage.
* Le logiciel est personnalisable, et les forums publics et la documentation soutiennent cela
* Il n'y a pas d'accès fournisseur pour la personnalisation et la correction des bogues.
* Les projets logiciels abandonnés peuvent être adoptés par de nouvelles équipes de développement.
* Les standards ouverts sont généralement utilisés, plutôt que des standards propriétaires.
* Les bogues et les problèmes de sécurité peuvent être rapidement résolus avec des correctifs logiciels.

### Qu'est-ce que la GPL ?
La GPL est l'abréviation de (GNU) General Public License ((GNU) Licence Publique Générale). Il est parfois appelé une licence copyleft, contrairement au copyright, car elle inverse les termes du copyright sur le logiciel. Plutôt que de restreindre la distribution, le copyright GPL est utilisé pour spécifier la propriété du code source et les termes selon lesquels il peut être partagé. La GPL a été créée par Richard Stallman en 1989 et est la licence fondatrice des logiciels open source. Son but est de protéger quatre libertés fondamentales qui sont considérées comme les fondements du logiciel libre. Ainsi, si une œuvre dérivée d'un logiciel sous licence GPL est redistribuée sous sa forme originale ou modifiée, elle doit être sous licence GPL, sinon la licence d'utilisation du programme source prendra fin et les conditions d'utilisation seront violées. Cela permet de rattacher un projet de logiciel libre à un nouveau projet, à condition que le nouveau projet soit sous la même licence. Il y a eu trois versions de la licence GPL au fil du temps. Kiwix est distribué sous GPLv3.

