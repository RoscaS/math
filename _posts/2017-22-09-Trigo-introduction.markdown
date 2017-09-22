---
layout: post
title: "Trigo: Introduction"
subtitle: ""
date: 2017-09-22
author: Sol
category: Trigo
tags: "Trigo"
finished: false
mathjax: true
---

## Conventions

### Notations

<img src="/01illustrations/01-trigo/01-intro/fig1.png" height="300">

$A,B,C:$ **sommets** du triangle
$a,b,c: $ **longueurs** des cotés ($a$ opposé $A$)
$\alpha,\beta,\delta:$ **amplitude** des angles ($\alpha$, angle de somment $A$)

### Sens d'un angle
* Une rotation dans les **sens inverse** des aiguilles d'une montre sera liée à un **angle positif**.
* Une rotation dans le **sens des aiguilles** d'une montre sera liée à un **angle négatif**.

## Mesure d'un angle
La mesure d'un angle consiste à _préciser_ de **combien** on _tourne_ pour amener le coté initial sur le coté final:

<img src="/01illustrations/01-trigo/01-intro/fig2.png" align="" height="300">

$$\LARGE \theta = ?$$

On décrète que:
* Un **tour complet** (qui ramène le segment $OA$ sur lui-même) vaut $360$ unités d'angle.
* Une unité d'angle est appelée **degré** et est notée ($^\circ$)

## Minute d'arc

Quand on mesure les ngles en degrés, on peut augmenter la précision de 2 façons:

* En exprimant les drés à l'ide de **nombres réels**: $\theta = 1.635 ^\circ, \theta = 1.33 ^\circ, \theta = \frac{1}{7}^\circ, \theta = \sqrt[]{2}^\circ,$ ...
* En subdivisant chque degré en **60 minutes** et en subdivisant chaque minute en **60 secondes**

### Degré $\rightarrow$ DMS
>Un degré équivaut à 60 minutes qui sont égales à 3600 secondes:
>$1 ^\circ = 60' = 360''$

$$\begin{align}
dd & = \text{angle initial} \\
D & = int(dd) \\
M & = int((dd - D) * 60) \\
S & = (dd-D-M/60) \cdot 3600 \\
     & \Rightarrow angle\;initial = DMS  \\ 
\end{align}$$

**Exemple:**

$$\begin{align}
    dd & = 36,25 ^\circ \\ 
    D & = int(dd) & = 36 ^\circ \\
    M & = int((36,25-36)\cdot60) & = 15' \\
    S & = (36,25-36-15/60)\cdot 3600 & =
\end{align}$$
