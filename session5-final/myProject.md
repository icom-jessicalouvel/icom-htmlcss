# ICOM - Cours HTML / CSS #

* Jessica LOUVEL
* jessica.louvel@gmail.com

## Pourquoi mon projet est-il organisé de cette manière ? 
### _(Avantages et inconvénient de cette organisation)_

Mon projet est composé d'un fichier HTML qui contient les balises qui structurent mon site, avec des balises générales qui englobent de façon indentée les balises qu'elles contiennent. 

D'un dossier "img" qui contient toutes les images que j'ai utilisé pour mon site. 

Ainsi qu'un dossier "stylesheets" qui contient 3 fichiers .css qui permettent de styliser le code HTML :
-global.css : pour les balises principales présentes dans toutes les pages du site (header, nav, footer, p, etc)
-home.css : pour les balises spécifiquement présentes dans la page d'accueil de mon site (le contenu, les articles, les images, etc)
-mediaqueries.css : pour déterminer une grille qui permet au site de s'adapter de façon responsive, selon les différents écrans sur lesquels s'affichera le code (pc, smartphone, tablette)

Le fait de séparer les fichiers css permet de s'y retrouver plus facilement. Il en vient de même pour les différents dossier. Cela peut aussi être un inconvenients car il faut ouvrir plusieurs fichiers à la fois et jongler entre ceux-ci

La structure en grille permet de donner des largeurs en pourcentage qui permettront aux différentes div de s'adapter à chaque écran, d'avoir une organisation optimale selon les dimensions de l'écran et donc d'avoir un site lisible et ergonomique sur tout type d'écrans et donc pour tout type d'internaute. Cependant cela rajoute un fichier spécifique, ce qui alourdit le site, et il faut rajouter différents id aux balises impactées. 

Le fait de mettre le code HTML qui correspond au global.css et qui donc présent sur chaque page, rend le fichier HTML un peu moins lisisble que si l'ont avait créé un fichier .php avec le header et le footer qui se retrouvent sur chacune des pages du site. Il suffirait alors de remplacer toutes les lignes correspondantes par une ligne d'appel vers le fichier .php et n'avoir alors que le contenu spécifique à la page html en question sur le fichier .html ce qui le rendrait bien plus lisible.


## Comment suis-je arrivé à ce résultat ?
### _(Différentes étapes, problématiques d'organisation)_

J'ai d'abord créé la structure HTML dans un fichier site.html, en partant du plus général (balises englobantes) pour aller jusqu'aux détails (articles, paragraphes...). 

J'ai ensuite créé le CSS, toujours en commençant par le général (disposition des div principales) : le header (logo + navigation) et le footer (top et bottom) dans un fichier global.css. 

Puis dans un fichier home.css, l'image d'accueil, suivis de la zone de contenu, ses trois colonnes et enfin les différents éléments qui composent les 3 colonnes. 

J'ai ensuite adapté le code HTML pour qu'il corresponde à la grille établie par les mediaqueries créés d'un nouveau fichier mediaqueries.css pour enfin éliminer ou modifier les styles inutiles dans les précédents css. 


___
## Quelles sont les diffucultés rencontrés durant ces 6 sessions ?

Le démarrage a été compliqué, surtout pour déterminer comment écrire la structure principale du code. Il m'a aussi fallut un temps pour visualiser le fonctionnement des mediaqueries avant de savoir comment l'appliquer au code HTML. J'ai enfin également eu du mal à comprendre le fonctionnement de GitHub et à faire mes premiers repositrories.