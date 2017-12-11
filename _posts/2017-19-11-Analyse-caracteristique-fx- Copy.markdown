---
layout: post
title: "Analyse: Caractéristiques d'une fonction"
subtitle: ""
date: 2017-11-19
author: Sol
category: Analyse
tags: ""
finished: false
mathjax: true
---

# Définition d'une fonction

$$\begin{align}
    f: \quad & \pmb{\mathbb{A}} \longrightarrow \pmb{\mathbb{B}} \\ 
    & x \longmapsto y =f(x) 
\end{align}$$

* $A$: Ensemble de départ ($=$ domaine de définition)
* $B$: Ensemble d'arrivée ($\neq$ ensemble Image)
* $f$: Nom de la fonction
* $x$: Un élément quelconque de l'ensemble $A$
* $y = f(x)$: Un élément de $B$. Désigne la valeur numérique associée à $x$ (dont $x$ est l'antécédent)
<br>
* La ligne du haut décrit la fonction au **niveau des ensembles**. Une flèche simple relie l'ensemble de départ à l'ensemble d'arrivée.
* La ligne du bas décrit la fonction au **niveau des éléments**. La flèche du bas remplace le verbe "associer".

# Domaine de définition $D$ (= ensemble de départ)

Le domaine de définition $D$ d'une fonction $f$ est l'ensemble des vleurs $x$ de $\pmb{\mathbb{R}}$ pour lesquelles $f(x)$ est définie.

$$ D = \{x \in \pmb{\mathbb{R}}|f(x)\in \pmb{\mathbb{R}}\} $$

## Exemples

1. Le domaine de définition de la fonction **polynomiale** $y=f(x)=2x-3$ est $D = \pmb{\mathbb{R}} $

2. Le domaine de définition de la fonction **rationnelle** $y=f(x)=\frac{2}{x-3}$ est $D = \pmb{\mathbb{R}} \setminus \{-3\} $

3. Le domaine de définition de la fonction **irrationnelle** $\sqrt[2]{x^2-9}$ est $D = \pmb{\mathbb{R}} \; \setminus \;]-3;\;3[ $

4. Le domaine de définition des fonctions **exponentielles** est $D=\pmb{\mathbb{R}}$

5. Le domaine de définition des fonctions **logarithmiques** est $D=\pmb{\mathbb{R^*_+}}$

6. Le domaine de définition des fonctions trig $sin$ et $cos$ est $D = \pmb{\mathbb{R}}$
6. Le domaine de définition des fonctions trig $tan$ et $cot$ est restreint à certaines valeurs de $x$


# Ensemble image $I$

L'ensemble image $I$ de la fonction $f$ est le sous ensemble de $B$ constitué de toutes les valeurs possibles de $f(x)$ lorsque $x$ est dans $A$.

$$ I = f(A) \text{ et } I \subseteq B $$

## Exemples

Soit: 

$\begin{align}
    f: \quad & \pmb{\mathbb{R}} \longrightarrow \pmb{\mathbb{R}}  \color{gray}{\quad E_{arr}}\\ 
    & x \longmapsto y =f(x) = x^2 
\end{align}$

L'ensemble image $I$ est $\pmb{\mathbb{R_+}}$

Beaucoup de formules que l'on rencontre en math et en science ne sont rien d'autre que des fonctions. Ainsi la formule $A=\pi\cdot r^2$ de l'aire d'un cercle de rayon $r$ fait correspondre à chaque nombre réel positif $r$ exactement une valeur $A$. La lettre $r$, qui représente une nombre quelconque du domaine de définition, est la **variable indépendante**. La lettre $A$, qui représente un nombre de l'ensemble image, est une **variable dépendante**, puisque sa valeur dépend de la valeur attribuée à $r$. Lorsque deux variables sont liées de cette façon, on dit que **$A$ est une fonctionde $r$**. De même lorsqu'une voiture roule à la vitesse de $60km/h$ la distance en $km$ qu'elle parcourt en $t$ heures est donnée par $d = 60 \cdot t$, la distance $d$ apparait ainsi comme une fonction du temps $t$.

# Interprétation graphique

Un graphique permet d'examiner le comportement des valeurs de $f(x)$ pendant que $x$ varie dans le domaine de définition de la fonction $f$. Par définition **le graphique d'une fonction $f$**(ou **la courbe représentative $C$**) est le graphique de l'équation $ y=f(x)$ pour $x$ dans le domaine de définition $f$.

$$ P(x,y) \in C \quad \Leftrightarrow \quad x \in D \text{ et } y=f(x)$$

<!-- <div>
    <iframe scrolling="no" title="Domain and Range of a Function" src="https://www.geogebra.org/material/iframe/id/fxsjcrzX/width/540/height/380/border/888888/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/false/ctl/false" width="540px" height="380px" style="border:0px;"> </iframe>
<div> -->


> Range = Ensemble Image $I$

* $y=f(x)$ est l'**image** de $x$ et $x$ est l'**antécédent** de $y=f(x)$

# Courbe, fonction, application / injectivité, surjectivité, bijectivité

Pour être qualifié de:

* **Fonction**: Pas plus d'une image par élément de l'ensemble de départ ($E_{dep}$) aussi non il s'agit d'une **Courbe**

* **Application** Tous les éléments de l'ensemble de départ ont une image (deux éléments de l'ensemble de départ peuvent avoir la même image).

<span style="color:green"> Pour transformer une **fonction** en **application** on réduit son ensemble de départ.</span>

* Application **injective**: Les éléments de l'ensemble de départ ont des images différentes.
$$ f(x_1) = f(x_2) \Leftrightarrow x_1 = x_2 \quad \text{ ou } \quad x_1 \neq x_2 \Leftrightarrow f(x_1) \neq f(x_2)$$

<span style="color:green"> Pour transformer une **application** en **application injective**, on modifie l'ensemble de départ.</span>

* Application **surjective**: Tous les éléments de l'ensemble d'arrivée ont des antécédents. 

<span style="color:green"> Pour transformer une **application** en **application surjective**, on modifie l'ensemble d'arrivée.</span>

On parle d'application **bijective** quand une application est à la fois injective **et** surjective. Cela veut dire que chaque élément de l'ensemble de départ a une unique image différente des autres éléments de l'ensemble de départ et que chaque élément de l'ensembe d'arrivée a un antécédent.