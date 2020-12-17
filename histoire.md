# HiSTOiRE DU SHELL

Le shell fut créé car une des particularités des systèmes UNIX, un système d'exploitation multi-utilisateurs et multi-tâches développé par AT&T, est de ne pas intégrer de langage de commande. 

Le premier shell créé fut développé par Ken Thompson (informaticien, concepteur des systèmes UNIX) en 1971, appellé _V6 shell_. Bien sûr, il ne possédait pas toutes les fonctionnalités qu'on les shell d'aujourd'hui. Il n'était pas complet, d'ailleur il fallait avoir une extention appelé _glob_ pour être au maximum de ses capacités. Finalement il ne servait simplement qu'à être une "invite de commande", puisque ce shell ne pouvais pas créer de srcipt.

Ensuite en 1977, Stephen Bourne (de l'AT&T Bell Labs) conçu le Bourne shell. Ce shell s'utilise encore aujourd'hui et est même parfois choisi comme shell par défaut sur certaine machine. Ce shell interactif s'est vu de multpiples améliorations comme le fait de pouvoir écrire et exécuter des scripts et utilser des boucles, variables et bien encore dedans. 

Mais là encore, le shell n'est pas assez complet, il n'a pas beaucoup de fonctionnalité, bien qu'il soit très leger et disponible partout.

L'année suivante la distribution BSD (Berkeley Software Distribution), sous la direction de l'informaticien Bill Joy, mit au point le C shell.

Cinq années plus tard, en 1983, le C shell incorporait des fonctionnalités du système Tenex. Tenex rajoutait en plus des noms de chemin et de fichier ainsi que l'édition de la ligne de commande. Ceci donna le C shell Tenex (tcsh), et ce fut l'oeuvre de Ken Greer. Il était compatible avec le C shell tout en l'améliorant.

Parallèlement mais durant la même pédiode, David Korn développa le Korn shell. Il ajouta ici la possiblité au Bourn Shell de créer des scripts.
Ce n'est qu'en 2000 qu'il sera modifié puisqu'il sera libérer en open source (il fournit les fonctionnalités d'autre shell).

Ensuite l'ont voulu changer, le Bourne Shell était dépassé. C'est ce qu'a fait Brian Fox, qui créa alors le Bourne Again Shell (bash) et deviens par la suite l'un des shells les plus repandus. Il s'agit d'enfaite un projet GNU (système d'exploitation libre) open source.

Enfin en dernier lieu viens le Z Shell, ou Zorn Shell. Il fut initialement créé en 1990 par Paul Falstad (étudiant à l'université de Princeton). C'est enfaite une sorte de Bourne Shell avec beaucoup d'amélioration, il reprend d'ailleur les meilleurs fonctionnalités du Bourne Again Shell,du Korn Shell et du C Shell Tenex. Il s'agit du plus récent shell, je l'utilise d'ailleur pour mon ordinateur, mais il n'est pas disposible sur toutes les machines, ce qui le rend pour certain inaccessible .
