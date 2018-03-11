---
layout: post
title: "Analyse: Applications des dérivées"
subtitle: ""
date: 2018-11-03
author: Sol
category: Analyse
tags: ""
finished: false
mathjax: true
---

## Définitions
Soit $f: I\Rightarrow \mathbb{R}$

### Point critique
$x_0$ est un point critique de $f$ si $f
'(x_0)=0$. Autrement dit, quand la pente $m$ de $f = 0$

### Maximum local
Si il existe un interval ouvert $J$ contenant $x_0 | \forall x \in I \cap J f(x) \leq f(x_0)$ alors $x_0$ est un **maximum** **local** (à l'interval $J$).

### Minimum local
Si il existe un interval ouvert $J$ contenant $x_0 | \forall x \in I \cap J f(x) \geq f(x_0)$ alors $x_0$ est un **minimum** **local** (à l'interval $J$).

### Extremum local
Notion qui reprend les deux précédentes: Un extremum local est soit un minimum local soit un maximum local.

### Maximum global
Si $|x\in I f(x) \leq f(x_0)$ alors x_0 est le maximum global.

### Maximum global
Si $|x\in I f(x) \geq f(x_0)$ alors x_0 est le minimum global.

> Un maximum global est aussi un maximum local mais pas l'inverse

### Regroupement des notions précédentes
Soi $I$ un interval ouver et $f:I\rightarrow \mathbb{R}$ une fonction dérivable. Si $f$ admet un maximum (ou minimum) local en $x_0$ alors $f'(x_0)=0$

> Logique, au sommet de la crète ou dans le creu, la pente vaut $0$.

* Si on a un extremum local alors on a un point critique mais la réciproque est généralement fausse (point d'inflexion)

* Dans le cas d'un interval fermé, attention aux extrémités qui peuvent être des extremum sans que $f'(x)$ en ces points ne soit $= 0$.

* Pour  déterminer $max_{[a;\;b]}f$ et $min_{[a;\;b]}f$ il faut comparer les valeurs de $f$ aux différents points critiques **et** en $a$ et en $b$.


## Applications

### Monotonie

Soit $f$ une fonction continue et dérivable sur l'interval $I$ alors:
* Si $f'(x) > 0$ sur $I$ alors $f$ est croissante sur $I$
* Si $f'(x) < 0$ sur $I$ alors $f$ est décroissante sur $I$
* Si $f'(x) = 0$ sur $I$ alors $f$ est monotonne


### Concavité
Soit $f$ une fonction continue et dérivable sur l'interval $I$ alors:

* Si $f''(x) > 0$ sur $I$ alors $f(x)$ est convexe sur $I$
* Si $f''(x) < 0$ sur $I$ alors $f(x)$ est concave sur $I$

### Point anguleux et Point de rebroussement

* Le point $P(a;\;f(a))$ est anguleux si $f_{gauche}'(a) \neq f_{droite}'(a)$ et au moins une de ses dérivées (gauche ou droite) $\neq \pm \infty$.
* Le point $P(a;\;f(a))$ est un point de rebroussement si $f_{gauche}'(a) = \pm \infty$ et si $f_{droite}'(a) = \pm \infty$

### Dérivabilité et continuité
Une fonction est dérivable en un point si elle est continue en ce point. **La réciproque n'est pas valable (points anglueux par exemple)**

### Point d'inflexion 
C'est un point où la fonction change de concavité. Graphyquement, en un point d'inflexion, la tangente coupe la courbe $\Rightarrow$ En ce point la dérivée seconde (si elle existe) s'annule et change de signe.

## Théorèmes

### Théorème de Rolle

Soit $f:[a;\;b] \rightarrow \mathbb{R}$ telle que:
* $f$ est continue sur $[a;\;b]$
* $f$ est dérivable sur $]a;\;b[$
* $f(a) = f(b)$
Alors il existe $c \in \; ]a;b[\;|\;f'(c)=0$

> * Ce théorème ne nous dit pas comment trouver $c$, il affirme uniquement l'existance de ce dernier. 
> * Rien ne nous dit que $c$ est unique.

## théorème des accroissements finis
Soit $f:[a;\;b]\rightarrow \mathbb{R}$ une fonction continue sur $[a,\;b]$ et dérivable sur $]a,\;b[$, alors il existe $c \in\;]a,\;b[\;|\; f(b)-f(a) = f'(c)(b-a)$.

Autrement dit, il existe au moins une valeur $c\;\in\;]a,\;b[$ de pente moyenne, c'est à dire: $f'(c)=\frac{f(b)-f(a)}{b-a}$

<img src="/01illustrations/acc_finis.png" align="" height="300px">
<br>

> La corollaire de ce théorème nous permet d'étudier la monotonie de la fonction (voir plus haut).




<div style="margin-bottom:500px"> </div>