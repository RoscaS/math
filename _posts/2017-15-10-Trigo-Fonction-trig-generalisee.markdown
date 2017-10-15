---
layout: post
title: "Trigo: Fonction trigonométriques généralisées"
subtitle: ""
date: 2017-10-15
author: Sol
category: Trigo
tags: "Trigo"
finished: false
mathjax: true
---

Considérons la fonction $sinus$ et opérons 4 types de transformation:

## Définition et nomenclature
Soit la fonction:

$$y = \color{blue}{A} \cdot sin(\color{red}{\alpha} x- \color{green}{\phi}) + \color{orange}{b} $$

1. $ \color{blue}{A} \Rightarrow $ **amplitude** : dilatation ou contraction verticale 
2. $ \color{red}{\alpha} $ **vitesse angulaire** : dilatation ou contraction horizontale 
3. $ \color{orange}{b} \Rightarrow$ **décalage vertical** : déplacement vertical
4. $ \color{green}{\phi} \Rightarrow $ **déphasage** : déplacement horizontal 

* $\frac{2\pi}{\alpha} \Rightarrow$ **période**, on la note $T=\frac{2\pi}{\alpha}$
* $\frac{\phi}{\alpha} \Rightarrow$ **phase à l'origine**

<br>

<div>
    <iframe scrolling="no" title="Fonction trigonométrique généralisée" src="https://www.geogebra.org/material/iframe/id/q8PwDnWn/width/1000/height/481/border/ffffff/smb/false/stb/false/stbh/false/ai/false/asb/false/sri/false/rc/false/ld/false/sdz/true/ctl/false" width="800px" height="481px" style="border:0px;"> </iframe>
</div>

## $\color{blue}{A} \Rightarrow $ **amplitude** : dilatation ou contraction verticale

* La multiplication de $sin(x)$ par un facteur $A$ change l'**amplitude**.
* La position de la courbe par rapport aux axes n'est pas modifiée.
* Les points d'intersection avec l'axe des x ne changent pas.

Les valeurs de $y$ sont entièrement comprises dans une bande allant de $y = -A$ à $y=A$

$$\bbox[5px,border:1px solid red] { y \in [-A, A]}$$

## $ \color{red}{\alpha} $ **vitesse angulaire** : dilatation ou contraction horizontale 
Considérons la fonction $ y = sin(\color{red}{2}x)$ et déterminons les points d'intersection avec l'axe des $x$.

On sait que $sin(\color{red}{x})$ vaut $0$ quand $\color{red}{x}$ vaut $\pi$ par exemple. Donc $sin(\color{red}{2x})$ vaudra $0$ quand $\color{red}{2x}$ vaudra $\pi$.

La courbe $sin(\color{red}{2}x)$ coupera l'axe des x si $\color{red}{2}x = \pi$ donc si $x=\frac{\pi}{2}$.


On constate que la fonction $sin(2x)$ a une période réduite d'un facteur $2$. Notons $T$ cette période, nous avons:

$$\begin{align}
    y & = sin(x) & \quad & \Rightarrow \quad T =2\pi \\ 
    y & = sin(\color{red}{2}x) & \quad & \Rightarrow \quad T = \frac{2\pi}{\color{red}{2}} \\ 
    y & = sin(\color{red}{\alpha}x) & \quad & \Rightarrow \quad T = \frac{2\pi}{\color{\alpha}{2}} \\ 
\end{align}$$


>La multiplication de la variable par un facteur change **la période**: $sin(\color{red}{\alpha}x)$ est  $\frac{2\pi}{\color{red}{\alpha}}$ périodique.

## $ \color{orange}{b} \Rightarrow$ **décalage vertical** : déplacement vertical


>L'ajout d'une constante $\color{red}{b}$ déplace **verticalement** le graph de la fonction.

## $ \color{green}{\phi} \Rightarrow $ **déphasage** : déplacement horizontal 
Considérons la fonction $y=sin(x-\color{red}{\phi})$ et cherchons ses intersections avec l'axe des $x$:

Nous savons déjà que $y=0$ si $x-\color{red}{\phi}=\pi$ par exemple, donc $x = \pi + \color{red}{\phi}$. Ceci etant valable pour toutes les autres intersections avec l'axe des $x$.


>On constate que le fait de **soustraire** $\phi$ à **la variable $x$**  décale le graphe de la fonction vers la droite si $\phi>0$ et vers la gauche si $\phi < 0$.

<span style="color:red"> Soustraire $\phi$ à la variable signifie que:  </span>
* $sin(4x)$ devient $sin(4\left(x-\frac{\phi}{4}\right))$ qui est bien **décalée de $\phi$**

$$\color{red}{\text{par contre}}$$

* $sin(4x-\phi) = sin(4\left(x-\frac{\phi}{4}\right))$ et est **décalée de $\frac{\phi}{4}$ seulement!**
