# Notes de lecture

Ce sous-dossier contient les documents utilisés comme références pour le projet.

Ce document permet de noter les points importants extraits de ces documents, ainsi que quelques remarques.

## Document `SMC_intro`

Titre : **Introduction to Sequential Monte Carlo Methods**

_TODO_

## Document `SMC_samplers`

Titre : **Sequential Monte Carlo samplers**

_TODO_

## Document `GraphMatching_SMC`

Titre : **Graph Matching via Sequential Monte Carlo**

_TODO_

## Document `JigsawPuzzle_SMC`

Titre : **Sequential Monte Carlo for Maximum Weight Subgraphs with Application to Solving Image Jigsaw Puzzles**

#### Notes

+ Explorer **"A probabilistic jigsaw puzzle solver", Cho et al., 2010** pour leur définition du problème de résolution de puzzle

+ Lire plus sur [**QAP**](https://en.wikipedia.org/wiki/Quadratic_assignment_problem) (Quadratic Assignment Problem) et [**MWS**](https://pdfs.semanticscholar.org/1f83/fcc896c1391effef722ea479512b841dde55.pdf) (Maximum Weight Subgraph)

+ Contraintes sur le problème : chaque pièce de puzzle n'est assignée qu'une seule fois, et chaque zone n'a qu'une pièce assignée

+ Différence fondamentale avec le _framework_ SMC habituel : les observations ne sont pas ordonnées, et les auteurs utilisent des permutations pour choisir la plus informative

+ 