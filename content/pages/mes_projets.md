---
Title: Mes projets
Date: 2023-04-24 14:30
Author: Thomas Bédrine
---

## Le problème à trois corps

En commençant mes études d'ingénieur il y a cinq ans, je pensais essentiellement me diriger vers le milieu des jeux vidéo. J'ai fait la connaissance de mon meilleur ami et futur colocataire, Bastien Barnéoud, également étudiant à l'UTBM. Sa propre passion pour l'espace m'ont rappelé à éveiller la mienne qui avait disparu pendant mon enfance, et en __septembre 2019__ nous avons étudié le cas théorique du [problème à trois corps](https://fr.wikipedia.org/wiki/Problème_à_N_corps) dans le cadre d'un projet libre de six mois (le rapport est disponible [ici](https://utbmfh.pagesperso-orange.fr/doc/projets/AC20BB.pdf)). Nous avions alors réalisé plusieurs simulations en nous basant sur des résultats déjà découverts, et tenté de comprendre pourquoi il s'agissait d'un problème aussi épineux. C'est un projet dont nous sommes tous deux très fiers et il a marqué le début de mon parcours dans l'astronomie et l'astrophysique.

## Exo3D : des planètes qui tournent, en 3D

Deux ans plus tard, en __septembre 2021__, j'ai entamé mon premier stage de six mois en tant qu'assistant ingénieur au [Laboratoire d'Études Spatiales et d'Instrumentation en Astrophysique](https://lesia.obspm.fr/), à l'Observatoire de Paris. J'ai rejoint l'équipe du projet Exoplanet dont la mission était de retravailler de multiples aspects de l'un des plus grands catalogues d'exoplanètes au monde : [L'Encyclopédie des Planètes Extrasolaires](http://exoplanet.eu/). Ma contribution à ce projet a été le développement d'une extension Web pour la visualisation en 3D des exoplanètes du catalogue : [Exo3D](https://gitlab.obspm.fr/exoplanet/exo3d).

Nous avons atteint une première version aboutie intégrant le système solaire avec une majorité de fonctionnalités, toutefois la relativement courte durée du stage n'a pas permis d'aller beaucoup plus loin. Bien que ce projet ne soit pas en production ni même terminé, j'en suis extrêmement fier et j'espère pouvoir le poursuivre tôt ou tard avec l'aide de PYM, qui était mon tuteur pour ce stage et m'a appris presque tout ce que je sais aujourd'hui.

Je compte intégrer prochainement Exo3D à ce site, lorsque j'aurais un peu de temps.

## VIP : révéler des exoplanètes proches de leur étoile

Mon sujet de stage actuel - depuis __février 2023__ - au PSILab porte sur le projet public VIP : [Vortex Image Processing](https://github.com/vortex-exoplanet/VIP). Il s'agit d'un ensemble d'outils dédiés au pré-traitement et au traitement de cube de données obtenus par divers téléscopes, afin de révéler de potentielles exoplanètes massives proches de leur étoile. Une grande partie de ces outils était déjà disponible mais le plus souvent au sein de projets privés ou peu développés, aussi VIP concentre la plus grande quantité de fonctions de traitement et pré-traitement existante en open source.

Je suis cette fois-ci stagiaire en tant qu'ingénieur débutant, et je remplis divers missions qui visent à améliorer la qualité du package dans l'optique de proposer son intégration au projet [astropy](https://www.astropy.org/). Être associé à un projet d'une telle portée permettrait de démocratiser l'utilisation des divers outils que propose VIP auprès de la communauté scientifique, ce qui est l'objectif central du projet. Je travaille sous la supervision du post-doctorant en charge du maintien et du développement de VIP, [Valentin Christiaens](https://github.com/VChristiaens).

Mes ajouts jusqu'ici couvrent la conversion en orienté-objet de toutes les fonctions de traitement, mais aussi de leur documentation, de la création d'un tutoriel dédié à leur utilisation sous Jupyter Notebook ainsi que des tests vérifiant l'intégrité de ces ajouts. J'ai également optimisé le temps de test de manière générale pour pallier à la vérification de plusieurs fonctions chronophages. Je compte prochainement ajuster le fonctionnement de l'objet dédié aux algorithmes de traitement basés sur le PCA, et inclure un objet de type "Logger" pour l'affichage d'infos pour l'utilisateur.
