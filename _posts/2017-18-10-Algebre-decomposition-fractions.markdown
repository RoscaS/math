---
layout: post
title: "Algèbre(3): Décomposition en fractions simples"
subtitle: ""
date: 2017-10-18
author: Sol
category: Algebre
tags: ""
finished: false
mathjax: true
---
C'est une technique utile, entre autres pour le calcul de certaines intégrales et dans le calcul des transformées de Laplace.

La décomposition en fractions simples concerne les **fonctions rationelles irréductibles**:

$$ f(x) = \frac{N(x)}{D(x)}$$

Où $N(x)$ et $D(x)$ sont des **polynomes** tels que le degré de $N(x)$ <span style="color:red"> est inférieur </span> au degré de $D(x)$.

Si le degré du numérateur est **supérieur ou égle** au degré du dénominateur, on peut effectuer une **division polynomial** dont le résultat sera la **somme d'un polynome et d'une fonction rationnelle**:

$$\begin{align}
    \frac{N(x)}{D(x)} & = P(x)+\frac{R(x)}{D(x)}  \\ 
    & = \text{Polynome}+\frac{\text{Reste}}{\text{Fonction rationnelle irréductible}}
\end{align}$$

La décomposition en fractions simples poura alors s'appliquer à la partie $\frac{R(x)}{D(x)}. 

Les fonctions rationnelles irréductibles sont difficiles à traiter. Il est souvent utile de pouvoir les écrire comme **une somme** de fractions simples(dites aussi fractions partielles). Pour cel on se base sur le théorème suivant:

Soit: la fonction rationnelle:

$$\frac{N_\color{red}{k}(x)}{D_\color{red}{n}(x)}$$ 

irréductible avec $\color{red}{(k<n))}$,

Alors:

$$ \frac{N_k(x)}{D_n(x)} \equiv F_1(x) + F_2(x)+\cdots +F_r(x)$$

Donc:

$$ 
F_ \color{red}{i}(x) =
\frac
{
    A_ \color{red}{i}
}
{
    (
        p_ \color{red}{i}x +
        q_ \color{red}{i}
    )^{\alpha}
}
\color{green}{\text{ ou bien }}

\frac 
{
    A_ \color{red}{i} +
    B_ \color{red}{i}
} 
{
    (
        a_ \color{red}{i} x^2 +
        b_ \color{red}{i} x +
        c_ \color{red}{i}
    )^{\beta}
} $$

> Ce théorème nous assure l'existence d'une telle décomposition.

## Marche à suivre
... pour obtenir la décomposition en fractions simples d'une fraction rationnelle irréductible:

1\. **Si nécéssaire**, effectuer la division euclidienne et considérer, pour ce qui suit uniquement la partie irréductible:

$$ \frac { N_k (x) } { D_n (x) } \color{gray}{\text{ (on doit avoir} k < n)}$$

2\. Factoriser le dénominateur $D_n (x)$ de façon à le transformer **en produit** de soit:
* **facteurs linéaires** $(px + q)^n$
> et ou
* de **facteurs quadratiques irréductibles** <span style="color:gray">(pas de racines réelles, donc pas factorisables)</span>: $(ax^2+bx+c)^m$

3\. Pour chaque facteur $(px+q)^n$, écrire la somme des fractions simples:

$$ \frac{A_1}{px+q}+\frac{A_2}{(px+q)^2}+\cdots + \frac{A_n}{(px+q)^n}$$

4\. Pour chaque facteur $(ax^2+bx+c)^m$, écrire la somme des fractions simples:

$$ \frac { A_1 }{ px+q }+ \frac{ A_2 }{ (px+q)^2 }+ \cdots + \frac{B_m x + c_m}{(ax^2+bx+c)^m}$$

5\. Calculer les constantes $A_i, B_i, C_i$ en posant que la fraction rationnelle $\frac{N_k(x)}{D_n(x)}$ <span style="color:red"> doit être **identique** </span> à sa décomposition en fractions simples.

## Exemple
