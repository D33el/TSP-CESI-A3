Contexte
Depuis les années 90, il y a eu une véritable prise de conscience mondiale de la nécessité de réduire la consommation d'énergie et des émissions de gaz à effet de serre. Les premiers engagements sont apparus lors de la signature du protocole de Kyoto en 1997. Mais son entrée en vigueur n'a finalement eu lieu qu'en 2005 et de nombreux scientifiques ont jugé les efforts insuffisants pour ralentir le réchauffement climatique. Depuis, d'autres engagements plus ambitieux ont vu le jour (division par 4 des émissions d'ici 2050 pour la France par exemple, engagements de certaines grandes villes comme Paris). Mais la tâche est compliquée. Les pouvoirs publics et les collectivités territoriales n'ont pas la possibilité d'obliger les entreprises et les particuliers à changer leurs habitudes pour atteindre ces objectifs. L'action se porte donc avant tout à faire évoluer les comportements. L'économie et le recyclage des matières premières, l'amélioration des modes de transports et des performances énergétiques des bâtiments doivent devenir des priorités.

SUJET:

DESCRIPTION du projet :
L’ADEME (Agence de l’Environnement et de la Maîtrise de l’Energie) a récemment lancé un appel à manifestation d’intérêt pour promouvoir la réalisation de démonstrateurs et d’expérimentations de nouvelles solutions de mobilité pour les personnes et les marchandises adaptées à différents types de territoires.

Votre structure CesiCDP est déjà bien implantée dans le domaine. Aidé de nombreux partenaires, vous avez réalisé plusieurs études sur le thème de la Mobilité Multimodale Intelligente. Les nouvelles technologies de transport, plus économiques et moins polluantes ne sont pas sans poser de nouveaux défis notamment d’un point de vue de l’optimisation de la gestion des ressources. Mais ces problèmes de logistique du transport présentent un enjeu majeur pour l’avenir : ses applications sont nombreuses (distribution du courrier, livraison de produits, traitement du réseau routier, ramassage des ordures) et leur impact sur l’environnement peut être véritablement significatif.

Vous faites partie de l’équipe (4 personnes) mise en place par CesiCDP pour répondre à l’appel de l’ADEME. L’enjeu est d’obtenir de nouveaux marchés avec des financements très intéressants pour continuer à développer votre activité.

CesiCDP a décidé d’orienter son étude sur la gestion de tournées de livraison. Le problème algorithmique consiste à calculer sur un réseau routier une tournée permettant de relier entre elles un sous-ensemble de villes, puis de revenir à son point de départ, de manière à minimiser la durée totale de la tournée. Cette optimisation devra tenir compte du trafic prévu sur chaque axe pour les différentes tranches horaires.

L’idée est de proposer une méthode issue de la Recherche Opérationnelle pour générer une tournée de livraison correspondant à ce problème.

Le périmètre reste encore à préciser. Vous avez décrit une version de base du problème. Mais, afin de le rendre plus réaliste et retenir toute l’attention de l’ADEME, vous hésitez à ajouter des contraintes supplémentaires. Il faut s’attendre à ce qu’il soit ainsi plus dur à traiter.

Version de base

Le choix du modèle et le code en Python capable de résoudre des instances de taille importante (plusieurs milliers de villes)

Une étude statistique du comportement expérimental de l'algorithme

ORGANISATION de la realisation du projet:
L’échéance pour le dépôt des projets auprès de l’ADEME est fixé au 12 juillet prochain. Afin de tenir les délais et de préparer tous les rapports nécessaires, vous avez défini la feuille de route suivante :

- Modélisation formelle
- Conception algorithmique et implémentation
- Étude expérimentale
- Présentation du travail réalisé à votre équipe (en anglais) avant remise des livrables à l'ADEME

Chacune de ces étapes aboutira à un livrable que vous présenterez à votre responsable pour suivi et échanges. Ces livrables prendront la forme d’un Notebook présentant à la fois la démarche et le code correspondant (lorsqu’une implémentation est requise). L'aspect story-telling doit être privilégié dans la rédaction de chacun de ces Notebook.

Le code des différents livrables n'a pas à être au standard d'un code à industrialiser (pas besoin d'une grande modularité). Il doit en revanche rester lisible, commenté, et privilégier la performance. Il est fortement recommandé de suivre les recommandations PEP :

Livrables attendus:

Livrable 1 : Modélisation (check)

Objectif : Modéliser le problème au travers d'un Notebook Jupyter

Description :
Ce premier livrable présente le problème que vous traitez ainsi que son contexte, le reformule de manière formelle, et en étudie les propriétés théoriques, notamment de complexité. D’une part, vous devrez proposer une représentation formelle des données, du problème, et de l’objectif à optimiser (pensez bien à intégrer les contraintes supplémentaires que vous décidez de traiter). D’autre part, vous devez vous appuyer sur cette représentation formelle pour démontrer la complexité théorique du problème en question. Il est fortement recommandé d’intégrer à ce notebook des références bibliographiques vers des articles ou des ouvrages scientifiques.

Les méthodes de résolution ne sont pas à aborder lors de ce check. Vous aurez l'occasion de les étudier en détails dans les boucles suivantes.

Le point est réalisé avec le tuteur de projet vous permettant de bien valider votre modélisation avant l'implémentation. Les éléments pourront être modifiés avant d'être intégrés dans le livrables final du projet.

Livrable 2 : final du projet

Objectif : Présenter l'ensemble de la démarche réalisée, la réalisation technique et conclure sur les résultats obtenus

Description :
Ce livrable se compose de 3 parties :

PARTIE 1 : Modélisation

- Reprend les éléments de modélisation formelle mis à jour
- Décrit la méthode de résolution choisie : détails sur l'algorithme utilisé, c’est-à-dire la métaheuristique choisie et la modélisation du problème selon le formalisme de cette métaheuristique (voisinage, opérations de croisement…)

PARTIE 2 : Implémentation

- L’implémentation de votre algorithme
- L'implémentation des cas de tests
- Une démonstration du fonctionnement de cette implémentation, sur différents cas de test (pas besoin d’être exhaustif)

PARTIE 3 : Etude expérimentale

- Expliquer le comportement expérimental de votre solution. Cette partie du livrable devra proposer et implémenter un plan d’expérience complet démontrant les performances de votre algorithme, ses limitations, et les perspectives d’amélioration que vous proposez sur la base de votre analyse.
- La méthodologie de ce plan d’expérience, les analyses que vous proposerez sur la base des résultats statistiques obtenus, et les propositions d’améliorations que vous en déduirez, devront être justifiés de manière détaillée.
