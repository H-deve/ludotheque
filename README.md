gestion de ludothèque permettant de gérer un stock de jeux et des adhérents.

L'association Betton Ludique souhaite mettre en place un outil de gestion de ludothèque permettant de gérer un stock de jeux et des adhérents.

Au sein d'un groupe de 3 ou 4 personnes, vous devez implémenter une solution locale de bout en bout en proposant un modèle UML complet et une implémentation en java, couplée à une base de données SQL Express. Vous devez utilisez Eclipse et la plate-forme de partage de code github.

Comme pour n’importe quel projet, vous aurez un certain nombre de livrables à produire : Un dossier de spécifications, qui contient une description fonctionnelle de votre application (on pourra y retrouver en particulier les trois types de diagrammes UML vus au Greta). Ce dossier est rédigé pour une équipe de développement. Un manuel d’utilisateur qui est rédigé pour l’association, en distinguant les différents rôles prévus dans vos diagrammes de cas d’utilisation. Un manuel d’installation qui est rédigé pour l’association.

Cette application doit être pensée pour être enrichie facilement, pour intégrer d'autres fonctionnalités que vous pourrez proposer en vue d'une implémentation future, comme par exemple la gestion des dégradations, de favoris, la connexion à des services en lignes de référencement de jeux etc.

La ludothèque propose des adhésions d'un an, de date à date, actuellement à 15€. Cette adhésion est portée par une personne principale (l'adhérent) mais peut profiter à différentes personnes (son foyer, des amis...). Pour information, sachez qu'elle permet d'emprunter 2 jeux sur une période de 15 jours. Un retard de 15 jours est acceptable, au delà certaines alertes peuvent être levées. Les jeux sont vérifiés à chaque retour, toute dégradation est actuellement notée dans un cahier. Un chèque de caution de 60€ est associé à chaque adhésion. Ces paramètres peuvent être amenés à évoluer avec le temps.

Les informations concernant les adhérents portent sur le porteur principal de l'adhésion, ses coordonnées et les autres personnes qui peuvent utiliser la carte liée à cette adhésion, les différentes périodes d'adhésion, le dépôt d'un chèque de caution valide, un historique des différentes alertes liées à ce compte (retard, perte, dégradation...). Vous trouverez joint un livre des adhérents anonymisé (fichier excel).

Les informations concernant les jeux sont de deux niveaux : il faut considérer les différents jeux disponibles (titre, auteur, éditeur, règle du jeu, contenu initial) et les boites de jeux physiques présentes dans la ludothèque, qui ont peut être subies des modifications dans leur contenu, des dégradations etc. Le site internet trictrac montre l'étendue des informations qui peuvent être connues autour d'un jeu. Vous trouverez joint quelques documents liés aux informations des jeux (la liste des jeux, une fiche telle qu'elle existe actuellement)

Le programme doit permettre a minima de saisir un nouvel adhérent ou un nouveau jeu, de démarrer un emprunt, de gérer les emprunts et de disposer d'un historique.
