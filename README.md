# Le rucher voconce

L'objectif sur ce projet était de tester un générateur de site statique dont l'apprentissage est très simple.
On peut avoir besoin dans certains cas de créer un site statique, pour des raisons de performace ou d'absence de maintenance du CMS, dans des contextes où les mises à jour sont peu fréquentes, où il n'y a pas besoin de gérer des comptes utilisateurs, etc ...
En quelque sorte, pour les dinosaures du web, faire un site à la main, avec une éditeur WYSIWYG comme l'avait apporter Frontpage puis le couple Dreamviewer / Contribute.

De nombreux outils existent désormais, et je souhaitais en trouver un qui, principalement :
 - avait un éditeur HTML, pas de rédaction en markdown par exemple,
 - avait une courbe d'apprentissage très rapide,
 - gère le responsive,
- ...

Je me suis tourné vers Silex (https://www.silex.me/) et j'ai tenté de réaliser ce projet complet (site https://www.rucher-voconce.fr), car rien de tel qu'un mini-projet pour éprouver la robustesse d'une solution.

Au final, j'ai apprécié de Silex son extrême simplicité, son intégration avec GitHub bien que l'on ne puisse pas choisir le commentaire des commits, son déploiement (on envoi ses fichiers sur le FTP, rien de de plus).
Côté points négatifs, le positionnement des blocs n'est pas très robuste (peut être lié au template), quelques bugs HTML/CSS sont présents, et tout comme quand on souhaite faire une optimisation HTML, l'édition HTML directe est possible mais délicate pour que Silex retrouve ses petits.

En conclusion, bonne solution et à tester, mais si on a besoin d'éditer le code HTML pour une raison ou une autre, cela devient vite long.