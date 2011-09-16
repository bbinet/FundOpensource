Fixer les règles du jeu!
========================

C'est à nous de fixer des règles intelligentes, où tout le monde trouve son compte, et où le partage du boulot et des rétributions est équitable, juste. Ces règles doivent être à l'avantage de ceux qui jouent le jeu.

Ci dessous, des exemples de règles possibles à différents problèmes.


PROBLEME:
---------
Lorsque plusieurs développeurs d'un même projet sont volontaires pour le développement d'une fonctionnalité, comment choisir?
Il faut ici des règles pour éviter les luttes entre développeurs pour gagner le "marché". Un des buts du système est de rétribuer les développeurs de manière juste et non de tirer les prix au plus bas.

.. rubric:: Négociation interne

La solution la plus saine serait de laisser les développeurs négocier eux-mêmes en interne pour choisir le développeur en charge du développement.
Si cela ne fonctionne pas, il faudra procéder à un arbitrage: plusieurs possibilités sont proposées ci-dessous.

.. rubric:: Chacun son tour

On pourrait imaginer que le développeur soit choisi à tour de rôle parmi les volontaires.

.. rubric:: Vote

Un vote pourrait être effectué pour décider à qui est attribué le "marché" parmi les volontaires. Si le vote ne permet pas de trancher (égalité), on pourra basculer sur un système aléatoire.

Le vote pourrait être organisé:
 * soit parmi les cofinanceurs,
 * soit parmi les développeurs,
 * soit les deux.

.. rubric:: Aléatoire

Un mécanisme aléatoire pourrait décider à qui est attribué le "marché" parmi les volontaires. 

.. rubric:: Développer à plusieurs

Il serait intéressant de pouvoir partager un développement entre plusieurs développeurs, et partager également sa rétribution. Ce type d'arrangement doit se faire à l'amiable entre développeurs.
En cas de conflit, une règle d'arbitrage pourrait être d'attribuer le "marché" à un des développeurs selon une des méthodes précédentes.


PROBLEME:
---------
Comment est réparti l'argent récolté par un développement?

.. rubric:: Au développeur

Il est intégralement reversé au développeur qui a travaillé (ou réparti équitablement si plusieurs personnes ont participé).

.. rubric:: Partage

La rétribution pourrait également être toujours partagée entre les différents développeurs d'un projet (à condition que la répartition des demandes de fonctionnalités soit aussi équitable entre les développeurs).
Comment mettre cela en place concrètement?


PROBLEME:
---------
Comment s'assurer que les cofinanceurs paient bien le montant qu'ils avaient annoncé?

.. rubric:: Paiement à l'avance

Pour mettre en place la facturation à l'avance pour les cofinanceurs et le paiement à la livraison du développeur, on pourra jouer le rôle de tiers:
on encaisse le paiement des cofinanceurs, l'argent dort jusqu'à la fin du développement, puis lorsque celui ci est validé, l'argent est transféré au développeur.
Ce système aurait aussi l'avantage de générer de la trésorerie.

On peut imaginer un système où les cofinanceurs paient à l'avance:

 * soit lorsqu'ils choisissent de cofinancer une fonctionnalité.

Dans le cas où la fonctionnalité serait rejetée, où si on n'arrive pas à rassembler le financement (avant une deadline qui est à définir?), on procède alors à un simple remboursement.

Avantage: L'argent est disponible tout de suite, engagement fort des cofinanceurs (car immédiat).

Inconvénient: Le paiement immédiat risque d'être une barrière à l'entrée de nouveaux cofinanceurs. Remboursement à prévoir si le développement ne se fait pas.

 * soit lorsque que le montant à cofinancer est atteint.

Avantage: Rien à rembourser si le développement est rejeté ou si il n'a pas été possible de rassembler le financement. La barrière d'entrée psychologique est plus basse, car pas besoin de payer tout de suite. Un utilisateur pourrait être libre de se désengager.

Inconvénient: un utilisateur pourrait être libre de se désengager (c'est aussi un risque).

.. rubric:: Assurances

On pourra souscrire à des assurances spécifiques.

.. rubric:: Garde-fous

Par exemple:
 * Si un cofinanceur refuse de payer, il pourrait être banni du système.
 * ...

.. rubric:: Imiter des modèles existants

Il existe certainement beaucoup d'exemples d'entreprises qui sont confrontés à ce type de problématiques (je pense par exemple à Ebay): on pourra regarder quels sont les moyens de contrôles qui ont été mis en place.

cf. http://linuxfr.org/~ploum/30451.html


PROBLEME:
---------

Comment s'assurer que le développeur livre bien la fonctionnalité finalisée et conforme aux spécifications?

.. rubric:: Paiement à la livraison

Le paiement ne pourrait s'effectuer que lorsque la fonctionnalité est terminée et validée.

.. rubric:: Assurances

On pourra souscrire à des assurances spécifiques.

.. rubric:: Garde-fous

Par exemple:
 * Si un développeur ne livre pas la fonctionnalité (ou de manière incomplète), il ne pourra plus participer à un "marché" pendant une durée à fixer.
 * ...

cf. http://linuxfr.org/~ploum/30451.html


PROBLEME:
---------

Le développement pur de la fonctionnalité n'est pas forcément suffisant: il peut être nécessaire de faire une release ou de préparer des installeurs et/ou mettre à jour les paquets des distributions)

.. rubric:: Le développeur doit toujours préciser ce qui sera livré

C'est à négocier avec le développeur lors de la phase de discussion, mais dans tous les cas il faut que chacun soit bien au fait de ce qui sera livré:
 * au minimum: patch au code source uniquement
 * mieux: patch et intégration dans le trunk
 * encore mieux: patch, intégration dans le trunk, nouvelle release, et création d'un paquet remonté upstream aux distributions (ou création installeur si windows)


PROBLEME:
---------
Et si le montant du chiffrage n'est jamais atteint? On rembourse comment?

.. rubric:: Paiement lorsque le dev commence

Une possibilité serait de ne prélever l'argent des cofinanceurs uniquement lorsqu'il y a suffisamment de "promesses de cofinancement" et que le développement est prêt à démarrer.
L'inconvénient de cette approche, c'est que l'utilisateur risque de changer d'avis plus facilement que s'il est déjà un peu engagé en versant de l'argent.

.. rubric:: Paiement "à retardement"

Une autre possibilité:
lorsqu'un utilisateur décide de cofinancer un développement, on lui demande les informations qui nous permettront d'engager le paiement à retardement (numéro de carte bleue).
Dans quelle mesure est-ce réalisable et légal...?

.. rubric:: Paiement immédiat

Sinon il faut prélever l'utilisateur dés qu'il choisit de cofinancer, et le rembourser ultérieurement si le développement n'aboutit pas (un délai d'incubation qui expire).

Ce serait peut-être le plus logique pour l'utilisateur, car il paie le jour où il prend sa décision de cofinancement.
Et le moins risqué pour nous, car moins de risque de désistement au dernier moment, si les utilisateurs ont déjà payé.


PROBLEME:
---------
Un utilisateur a-t'il la possibilité de se dédire?

Oui!

Dans l'idéal, il faut que tout utilisateur soit libre, libre de changer d'avis par exemple. (cf. :doc:`Philosophie`)
Il faut donc en effet lui donner la possibilité de se dédire.

Cela risque de causer des problèmes d'organisation/gestion importants. Car si un développement est prêt à démarrer, et que des utilisateurs se désistent, le financement n'est plus assuré.

.. rubric:: Paiement immédiat

Si on prélève l'utilisateur dés qu'il choisit de cofinancer, le risque de désistement sera moins grand car il sera déjà un peu engagé. Il faut tout de même prévoir une procédure de remboursement si la demande de remboursement est faite avant le démarrage des développements.

On pourrait par exemple imaginer que si l'utilisateur se dédit, les frais bancaires que cela à coûté seront déduits du remboursement.


PROBLEME:
---------
Comment déterminer et controller les développeurs potentiels d'un projet?

.. rubric:: Droit de commit

Ils doivent avoir le droit de commit sur le repository du projet.
Le contrôle de la "validité" de ces développeurs peut d'abord être à la charge de la personne responsable du projet dans notre système. Ensuite, il pourrait être possible pour n'importe qui de reporter des abus. 


PROBLEME:
---------
Si les cofinanceurs ne sont pas tous d'accord sur le contenu du développement?

C'est le développeur qui propose la solution technique, et les cofinanceurs qui acceptent (ou pas). Si ils n'acceptent pas, le développement ne peut pas se faire, il faut attendre d'avoir plus de cofinanceurs (qui seront d'accords avec la solution technique proposée par le developpeur).

Et en cas de désaccord lors de la rédaction communautaire du cahier des charges par les utilisateurs intéressés?

.. rubric:: Système de vote

Il faudrait un système de votes très simple qui permettent de prendre les décisions après discussion. Ceci afin d'éviter les situations de blocage
.
On pourrait imaginer un sytème où chaque cofinanceur à une voix, et en cas d'égalité, le premier cofinanceur (celui qui a créé la demande) obtient une voix supplémentaire pour trancher.



