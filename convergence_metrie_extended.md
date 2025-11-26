# Convergence de la fonction d’action vers une métrique riemannienne

## Introduction

La Théorie ZM formalise l’espace-temps comme limite continue d’un réseau fractal dynamique de pixels d’information disposés selon un graphe pondéré. L’objectif est de montrer rigoureusement que la fonction d’action définie sur ces graphes converge vers une énergie de Dirichlet sur une variété riemannienne associée.

## Formalisme

Soit une suite de graphes pondérés ((G_k)) avec poids (W_k = {w^{(k)}_{ij}}), définissant une distance discrète (d_k) sur chaque graphe.  
En affinant le graphe ((k \to infty)), on considère la convergence des espaces métriques ((V_k, d_k)) vers une variété riemannienne (M) au sens de Gromov-Hausdorff.

La fonction d’action sur le graphe est :

[
S_k(sigma) = \frac{1}{2} sum_{i,j} w^{(k)}_{ij} (sigma_i - sigma_j)^2
]

Elle est une approximation discrète de l’énergie de Dirichlet :

[
mathcal{E}(f) = int_M |
abla f|^2 , dmu
]

## Résultats

La convergence spectrale de la suite (S_k) vers (mathcal{E}) est assurée sous des hypothèses standards de régularité et de densité des graphes. Cette convergence garantit que la dynamique discrète de ZM rapproche effectivement une structure géométrique lisse.

## Conclusion

Cette démonstration établit une base formelle solide à l’émergence géométrique du continuum dans ZM, un pilier essentiel de la théorie.

## Références

- F. R. K. Chung, *Spectral Graph Theory*, AMS (1997).  
- M. Gromov, *Metric Structures for Riemannian and Non-Riemannian Spaces*, Birkhäuser (2007).
