# Choix d'une palette de $k$-couleurs et recoloriage d'une image

Il s'agit d'un travail réalisé dans le cadre d'INF TC1 (rendu du TD6) qui s'intéresse au traitement colorimétrique des images.

## Elèves

Ce travail a été réalisé par Manon LECLERCQ (groupe de TD B2b) et Maxime LUCE (groupe de TD 1Aa).

## Contexte

La quantification de couleurs, ou réduction du nombre de couleurs dans une image, est une problématique centrale en traitement d’images. Elle consiste à représenter une image à l’aide d’un ensemble réduit de couleurs, tout en préservant au mieux son apparence visuelle. L’objectif de ce devoir est de mettre en œuvre un algorithme permettant de générer automatiquement une palette de couleurs optimale pour une image donnée. Cette palette devra être plus restreinte que le nombre de couleurs initialement présentes dans l’image, tout en restant la plus représentative possible de sa composition chromatique.

On retrouce ce processus dans de nombreux domaines d’application : compression d’images, affichage sur des périphériques à faible capacité graphique, création de versions simplifiées d’images pour l’impression ou le web, ou encore génération automatique de palettes pour le design graphique. Il est également utilisé dans des logiciels de traitement d’image comme Photoshop, Gimp ou Paint, et plus généralement dans tous les domaines où l’on cherche à simplifier une image sans en altérer la perception.

Sur le plan informatique, cette problématique soulève quelques questions algorithmiques : comment identifier les couleurs dominantes d’une image ? Comment choisir un bon compromis entre fidélité visuelle et nombre de couleurs utilisées ? Comment formaliser et mesurer la "représentativité" d’une palette ?

Ce devoir s’inscrit dans le prolongement du TD#4, où nous avons étudié le codage des couleurs en composantes rouge, verte et bleue (RGB). Nous allons ici approfondir cette notion en mettant en œuvre un algorithme de quantification de couleurs, en utilisant notamment les outils fournis par le langage Python et le module Pillow. Ce travail permet ainsi de mieux comprendre les enjeux liés à la représentation visuelle, à l’optimisation de données et à la perception humaine des couleurs.

## Organisation du dépot

- version_finale.ipynb qui contient le fichier Jupyter
- le dossier "Images_Non_Compresses" qui contient les images utilisées pour les tests avant compression ;
- le dossier "figures" qui provient du sujet de TD ;
- le dossier "img_notebook" qui contient les graphiques et images utilisées dans le notebook ;
- le dossier "old" qui archive certains fichiers ou versions ;
- les images (compressées) utilisées pour les tests dans le répertoire racine (par souci de simplicité d'utilisation dans le fichier jupyter)

## License

[![CC0](https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
CC BY-NC-ND 4.0

Attribution-NonCommercial-NoDerivatives 4.0 International
