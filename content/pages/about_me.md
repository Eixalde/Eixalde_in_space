---
Title: Eixalde in Space : développeur junior visant les étoiles
Date: 2023-04-24 12:00
Author: Thomas Bédrine
---

Bienvenue sur mon site web, réalisé grâce à [Pelican](https://getpelican.com/). J'ai été largement inspiré de mon ex-tuteur de stage et mentor [Pierre-Yves Martin](https://github.com/pymaldebaran) et ai décidé de mettre en lumière mon travail et mes passions via ce site.

### Qui suis-je ?

Je m'appelle Thomas Bédrine, et j'utilise fréquemment le pseudo Eixalde en ligne - notamment depuis mon propre [GitHub](https://github.com/Eixalde). J'ai 21 ans et je suis étudiant ingénieur en informatique à [l'Université de Technologie de Belfort-Montbéliard](https://www.utbm.fr/), spécialisé en imagerie numérique et en modélisation dans des environnements virtuels. Je suis actuellement en stage de fin d'études à [l'Université de Liège](https://www.uliege.be), dans le département [STAR](https://www.star.uliege.be) pour le [Planetary and Stellar system Imagery Laboratory](https://www.psilab.uliege.be).

Comme vous l'aurez peut-être deviné, je me passionne pour l'espace depuis déjà plusieurs années et j'ai décidé d'en faire mon domaine d'application. Toutefois, comme il ne s'agit pas de mon cursus principal, je reste relativement amateur en astrophysique et en astronomie et je contribue de mon mieux à l'avancement de la recherche en utilisant mes compétences de dev junior.

### Quelques projets

#### Le problème à trois corps

En commençant mes études d'ingénieur il y a cinq ans, je pensais essentiellement me diriger vers le milieu des jeux vidéo. J'ai fait la connaissance de mon meilleur ami et futur colocataire, Bastien Barnéoud, également étudiant à l'UTBM. Sa propre passion pour l'espace m'ont rappelé à éveiller la mienne qui avait disparu pendant mon enfance, et en __septembre 2019__ nous avons étudié le cas théorique du [problème à trois corps](https://fr.wikipedia.org/wiki/Problème_à_N_corps) dans le cadre d'un projet libre de six mois (le rapport est disponible [ici](https://utbmfh.pagesperso-orange.fr/doc/projets/AC20BB.pdf)). Nous avions alors réalisé plusieurs simulations en nous basant sur des résultats déjà découverts, et tenté de comprendre pourquoi il s'agissait d'un problème aussi épineux. C'est un projet dont nous sommes tous deux très fiers et il a marqué le début de mon parcours dans l'astronomie et l'astrophysique.

#### Exo3D : des planètes qui tournent, en 3D

Deux ans plus tard, en __septembre 2021__, j'ai entamé mon premier stage de six mois en tant qu'assistant ingénieur au [Laboratoire d'Études Spatiales et d'Instrumentation en Astrophysique](https://lesia.obspm.fr/), à l'Observatoire de Paris. J'ai rejoint l'équipe du projet Exoplanet dont la mission était de retravailler de multiples aspects de l'un des plus grands catalogues d'exoplanètes au monde : [L'Encyclopédie des Planètes Extrasolaires](http://exoplanet.eu/). Ma contribution à ce projet a été le développement d'une extension Web pour la visualisation en 3D des exoplanètes du catalogue : [Exo3D](https://gitlab.obspm.fr/exoplanet/exo3d).

Nous avons atteint une première version aboutie intégrant le système solaire avec une majorité de fonctionnalités, toutefois la relativement courte durée du stage n'a pas permis d'aller beaucoup plus loin. Bien que ce projet ne soit pas en production ni même terminé, j'en suis extrêmement fier et j'espère pouvoir le poursuivre tôt ou tard avec l'aide de PYM, qui était mon tuteur pour ce stage et m'a appris presque tout ce que je sais aujourd'hui.

Je compte intégrer prochainement Exo3D à ce site, lorsque j'aurais un peu de temps.

#### VIP : révéler des exoplanètes proches de leur étoile

Mon sujet de stage actuel - depuis __février 2023__ - au PSILab porte sur le projet public VIP : [Vortex Image Processing](https://github.com/vortex-exoplanet/VIP). Il s'agit d'un ensemble d'outils dédiés au pré-traitement et au traitement de cube de données obtenus par divers téléscopes, afin de révéler de potentielles exoplanètes massives proches de leur étoile. Une grande partie de ces outils était déjà disponible mais le plus souvent au sein de projets privés ou peu développés, aussi VIP concentre la plus grande quantité de fonctions de traitement et pré-traitement existante en open source.

Je suis cette fois-ci stagiaire en tant qu'ingénieur débutant, et je remplis divers missions qui visent à améliorer la qualité du package dans l'optique de proposer son intégration au projet [astropy](https://www.astropy.org/). Être associé à un projet d'une telle portée permettrait de démocratiser l'utilisation des divers outils que propose VIP auprès de la communauté scientifique, ce qui est l'objectif central du projet. Je travaille sous la supervision du post-doctorant en charge du maintien et du développement de VIP, [Valentin Christiaens](https://github.com/VChristiaens).

Mes ajouts jusqu'ici couvrent la conversion en orienté-objet de toutes les fonctions de traitement, mais aussi de leur documentation, de la création d'un tutoriel dédié à leur utilisation sous Jupyter Notebook ainsi que des tests vérifiant l'intégrité de ces ajouts. J'ai également optimisé le temps de test de manière générale pour pallier à la vérification de plusieurs fonctions chronophages. Je compte prochainement ajuster le fonctionnement de l'objet dédié aux algorithmes de traitement basés sur le PCA, et inclure un objet de type "Logger" pour l'affichage d'infos pour l'utilisateur.

### De quoi suis-je capable ?

La majeure partie de mon expérience en développement m'est venue de mes deux stages, je maitrîse donc d'une part le développement Web - essentiellement en front-end - avec JavaScript, HTML et CSS. J'espère faire la transition vers le TypeScript de manière générale dès que j'en aurais l'occasion, histoire de rester droit dans mes bottes et mon typage.

J'ai aussi fait énormément, ÉNORMÉMENT de Python, de mes simulations de trajectoire dans le problème à trois corps jusqu'à VIP aujourd'hui en passant par divers mini-projets et TP d'imagerie pendant mes cours. J'ai un peu tenté d'approcher MatLab, mais j'ai vite retrouvé mon compagnon serpentin.

Mes cours de spécialisation en 3D/VR m'ont aussi introduit à l'utilisation de Blender et d'Unity, encore que je ne les ai pas appliqués récemment donc il me faudrait quelques piqûres de rappel pour ne pas perdre la main. C'est dommage que je n'ai pas plus souvent l'occasion de faire du C# car c'est un langage que j'apprécie, pour l'heure je devrai me contenter du Python qui est de toute façon le roi incontesté en simulations astrophysiques.

Au-delà de tout ceci, j'ai appris à travailler en AGILE sur Git, avec de la gestion d'issues et plus récemment d'actions. J'ai aussi commencé à tester autant que possible toutes mes fonctions, et je ne me sépare jamais de [pre-commit](https://pre-commit.com/) pour vérifier que je ne suis pas la tête en l'air lorsque je commit mon travail et que je n'ai pas laissé de coquilles.

Dans une moindre mesure, je suis mordu de mathématiques depuis mon plus jeune âge et je peux parfaitement m'endormir en essayant de résoudre des problèmes débilement complexes. Je pense que dans un univers parallèle proche du nôtre, je serais devenu un prof de maths excentrique. Ce n'est pas forcément une compétence en soi, mais ça m'aide à apprécier et à assimiler des concepts assez velus en astrophysique donc je ne m'en plains pas.

### Qu'est-ce que j'aime faire ?

Parler d'Exo3D ou de VIP, d'espace ou de mathématiques en général. Je peux passer autant d'heures à me casser les dents sur un bug qu'à raconter à qui veut l'entendre que je fais tourner des planètes sous JavaScript. Mêler mes trois passions, l'informatique, l'espace et les mathématiques, a été la meilleure chose que j'ai pu entreprendre.

À part l'espace, j'ai un passé assez long avec les jeux vidéo, qui ont failli devenir ma vocation de fait. Je joue régulièrement mais sans catégorie précise, on retrouve quelques points redondants comme mon amour des jeux de rythme et des roms modifiées de Pokémon mais le reste est très épars et trop difficile à résumer. Je joue à ce qui m'inspire sur le moment, et je change environ une à deux fois par mois de cible - difficile de terminer quoi que ce soit dans ces conditions, mais j'aime le challenge !

Je lisais beaucoup avant mes études, essentiellement de la Fantasy et de la SF, mais à mon grand désarroi je ne me laisse plus beaucoup de temps pour replonger le nez dans mes livres. Je pense que j'en suis à une pile de 15 livres que je n'ai pas encore lus et qui attendent encore sur mon étagère, et elle ne cesse d'augmenter... Parmi mes sagas favorites on ne manquera pas de retrouver "Nous sommes Bob", une trilogie chère à mon coeur qui traite de copie de la conscience, d'intelligence artificielle, d'exploration spatiale et de paradoxe de Fermi ; ainsi que l'excellente "Saga d'Ender", un bijou de lore et de cohérence d'univers avec des personnages tous attachants et bien écrits, le tout sur fond de space opéra. Je ne peux que trop vous recommander de les lire si vous vous intéressez à l'espace comme moi.

À mes heures perdues, il m'arrive de prendre fil et aiguille et de broder, cependant c'est la passion chronophage par excellence. J'ai passé plus de 150 heures à réaliser 5 motifs de taille moyenne sur ma blouse d'étudiant et j'y passe rarement moins de 6 heures d'affilée. Pour des raisons évidentes de "réussir ma scolarité" et "avoir une vie sociale" je limite soigneusement le temps que je dédie à la broderie.
