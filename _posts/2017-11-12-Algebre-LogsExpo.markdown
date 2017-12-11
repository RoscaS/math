---
layout: post
title: "Algèbre: Logarithmes et exponentielles"
subtitle: ""
date: 2017-09-30
author: Sol
category: Algebre
tags: ""
finished: false
mathjax: true
---

# Les Logarithmes

La fonction logarithme est la fonction réciproque de la fonction exponentielle. Elle est donc utile pour résoudre les équations comportant des puissances.

Par exemple, la solution de l'équation $2^x=5\;$ est $\; log_2(5)$. 

## Introduction
Les logarithmes sont une autre façon de penser aux exposants.
On peut aussi dire que les logarithmes n'existeraient pas si les exposants n'existaient pas.

$\color{teal}{2}$ puissance $\color{green}{4}$ est égal à $\color{orange}{16}$.  Ce qui s'écrit: $\color{teal}{2}^{\color{green}{4}}=\color{orange}{16}$

Si on pose la question: _À quelle puissance faut-il élever $\color{teal}{2}$ pour obtenir $\color{orange}{16}$_ ? La résponse est $\color{green}{4}$. Si on utilise un **logarithme**, la relation qui lie 2, 4 et 16 est: $log_{\color{teal}{2}}(\color{orange}{16})=\color{green}{4}$ et se lit: _Le logartithme en base deux de seize est quatre_.

$$ \color{teal}{2}^{\color{green}{4}}=\color{orange}{16} \quad \Leftrightarrow \quad log_{\color{teal}{2}}(\color{orange}{16})=\color{green}{4}$$

Les deux égalités traduisent la même relation entre $\color{teal}{2}$ (**base**), $\color{green}{4}$ (**exposant**) et $\color{orange}{16}$ (**puissance**).

La différence entre ces deux égalités est que dans la forme exponentielle on isole la puissance de $\color{orange}{16}$, tandis que dans la forme logarithmique, on isole l'exposant $\color{green}{4}$.


Logarithmes | Puissances 
------------|----------
 $log_{\color{teal}{2}}(\color{orange}{8})=\color{green}{3}$ | $\color{teal}{2}^{\color{green}{3}}=\color{orange}{8}$
 $log_{\color{teal}{3}}(\color{orange}{81})=\color{green}{4}$ | $\color{teal}{3}^{\color{green}{4}}=\color{orange}{81}$
 $log_{\color{teal}{5}}(\color{orange}{25})=\color{green}{2}$ | $\color{teal}{5}^{\color{green}{2}}=\color{orange}{25}$

## Définition du logarithme de base $b$

Par définition si $\color{red}{a>0}$ et $\color{red}{b>0}$,

<br>
$$ \Large{log_{\color{teal}{b}}(\color{orange}{a})=\color{green}{c} \; \Leftrightarrow \; \color{teal}{b}^{\color{green}{c}}=\color{orange}{a}}$$

$\color{teal}{b}$ est la <span style="color:teal">base</span> de la puissance et c'est aussi la base du logarithme


$\color{green}{c}$ est <span style="color:green"> l'exposant </span> 


$\color{orange}{a}$ est la <span style="color:orange"> puissance </span> mais c'est aussi <span style="color:orange"> l'argument </span> du logarithme

>Quand on passe de la forme exponentielle à la forme logarithmique ou vice-vera, la base du logarithme et la base de l'exponentielle sont les mêmes.

## Propriétés de base

Logarithme | Exponentielle
---------|----------
 $log_b(1)=0$      | $b^0=1$ 
 $log_b(b)=1$      | $b^1=b$ 
 $log_b(b^x)=x$    | $b^{log_b(x)}=x$ 
 $log_b(u^p)=p\cdot log_b(u)$ | $(b^u)^p=b^{u\cdot p}$

## Ensemble de définition

$log_b(a)$ est défini pour toute la base $b > 0$ et $b \neq 1$ ainsi que pour tout argument $a > 0$. Ces conditions sont la conséquence directe des propriétés des puissances.

$b>a$: Les fonctions exponentielles de base $b$ ne sont définies que si $b$ est strictement positif.


$a>0$: $log_b(a)=c$ équivaut à $b^c-a$. Or toute puissance d'un nombre positif est positive. Donc $b^c>0$ et par conséquent $a>0$.


$b \neq 1$: Si $b$ _était_ égal à $1$ alors, par exemple, il existerait un nombre $x$ tel que $log_1(3)=x$ qui serait équivalent à $1^x=3$. Or toute puissance de $1$ est égale à $1$, donc un tel nombre $x$ n'existe pas, et donc $b\neq1$.

## Exemples tricky

  $$\bbox[5px,border:1px solid red] {log_{b^y}(a^x)=\frac{x}{y}}$$

$$ 1)\quad log_{64}\left(\frac{1}{4}\right) = log_{2^6}(2^{-2})  =-\frac{1}{3} $$


$$ 2)\quad log_{49}(7) = log_{7^7}(7) =\frac{1}{7} $$


$$ 3)\quad log_{4}\left(\frac{1}{2}\right) = log_{2^2}(2^{-1})=-\frac{1}{2} $$


$$ 4)\quad log_{4}(8) = log_{2^2}(2^3)=\frac{3}{2} $$

## Logarithme népérien

Noté $ln(x)$ le **logarithme népérien** est le logarithme de base $e$.

$$ log_e(x) = ln(x) $$

>$e$ est une constante. C'est un nombre irrationnel dont la valeur approchée au millième est $2,718$.

$$ e= \lim\limits_{n \to \infty}\left(1+\frac{1}{n}\right)^n\approx 2,7182$$

## Propriétés du logarithme


|        | Logarithme | Exponentielle |
|--------|----------|-----------------|
|**Produit**   |$$log_b(M\cdot N)=log_b(M)+lob_b(N)$$| $$b^M\cdot b^N=b^{M+N}$$
|**Quotient**  |$$log_b\left(\frac{M}{N}\right) = log_b(M)-log_b(N)$$|
|**Puissance** |$$log_b\left(M^N\right)=N\cdot log_b(M)$$ |

Ces égalités sont vraies pour tout $u$, $v$ et $b$ pour lesquels le logarithme est défini, c'est à dire pour tout $u$ et $v >0$ et tout $b<b \neq 1$

>La fonction logarithme de base $b$ est définie si $b$ est strictement positif et différend de 1, et l'ensembe de définition d'une fonction logarithme est $\pmb{\mathbb{R}_+}$

### Logarithme d'un produit

$$log_b(M\cdot N)=log_b(M)+lob_b(N)\; \Leftrightarrow b^M\cdot b^N=b^{M+N}$$

Le logarithme d'un produit est la somme des logarithmes de ses facteurs.

Si $M=4$, $N=8$ et $b=2$, alors d'après la propriété du logarithme d'un produit, $log_2(4\cdot 8) = log_2(4) + log_2(8)$.

Le calcul qui suit permet de vérifier la propriété dans ce cas précis:

$$\begin{align}
    log_2(4\cdot8)&=log_2(4)+log_2(8) \\ 
    log_2(32)&=log_2(4)+log_2(8) \\
    5&=2+3 \\
    5&=5
\end{align}$$

> On utilise cette propriété pour manipuler les expression logarithmiques

