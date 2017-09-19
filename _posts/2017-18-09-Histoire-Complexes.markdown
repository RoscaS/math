---
layout: post
title: "Histoire: Nombres complexes"
subtitle: ""
date: 2017-09-18
author: Sol
category: Histoire
tags: ""
finished: false
mathjax: true
---


# Imaginary numbers are real
* [playlist youtbe](https://www.youtube.com/watch?v=T647CGsuOVU&list=PLiaHhY2iBX9g6KIvZ_703G3KJXapKkNaF&index=1)


## Problème de Del Fierro

Au 15e siecle, le mathématicien [Scipione del Fierro](https://fr.wikipedia.org/wiki/Scipione_del_Ferro) (1465 - 1526) recherche une formule pour résoudre les équations cubiques.
Le cas général etant trop compliqué:
$$ax^3 + bx^2 + cx + d = 0$$ il commence par chercher une solution à une version simplifiée: 
$$ax^3 +cx  -d = 0$$ mais comme à cette époque les nombres négatifs sont encore évités l'équation ressemble plus à ça:
$$\require{cancel} \cancel{a}x^3 + cx \xcancel{-d} = 0 \text{ avec } a = 1$$ 

$$ \bbox[5px,border:1px solid black] 
    {x^3+cx=d}
$$

avec: $$c > 0$$ $$ d > 0 $$

Il trouve la solution mais la garde pour lui. Il ne la dévoilera qu'à son diciple **Antonio Foir** sur son lit de mort: 

$$ x = \sqrt[3]{\frac{d}{2} + \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}} + \sqrt[3]{\frac{d}{2} - \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}} $$

A la même période **[Niccolo Fontana Tartaglia](https://fr.wikipedia.org/wiki/Niccolo_Fontana_Tartaglia)**(1499, 1557), un autre mathématicien trouve lui aussi comment résoudre les équations cubiques et humilie Antonio Foir qui ne comprend pas l'essence de la résolution. Tartaglia ne dévoilera sa formule qu'à un autre grand mathématicien de l'époque nommé [**Girolamo Cardano**](https://fr.wikipedia.org/wiki/Girolamo_Cardano)(1501 - 1576) qui lui jure de ne pas la dévoiler. Bien sur, Cardano dévoilera la formule dont l'equation de base est légèrement modifiée dans un livre qu'il écrit.

Le problème de cette solution est que pour certaines valeurs de $c$ et de $d$, la formule ne fonctionne pas.
Et voici un exemple:

$$ \begin{align}
x^3 & = 15x + 4 \\
x & = \sqrt[3]{\frac{d}{2} + \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}} + \sqrt[3]{\frac{d}{2} - \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}}\\
x & = \sqrt[3]{\frac{4}{2} + \sqrt{\frac{4^2}{4}-\frac{15^3}{27}}} + \sqrt[3]{\frac{5}{2} - \sqrt{\frac{5^2}{4}-\frac{15^3}{27}}}\\ 
x & = \sqrt[3]{2+\sqrt{4-125}} + \sqrt[3]{2-\sqrt{4-125}}\\
x & = \sqrt[3]{2+\sqrt{-121}} + \sqrt[3]{2-\sqrt{-121}} \\ 
\end{align} $$

Cardano se retrouve coincé par **la problematique des racines négatives**. Deux nombres positif multipliés entre eux ne seront jamais négatifs. Pareil pour deux nombres négatifs.

$$\sqrt{9} = 3, -3$$ $$\sqrt{-9} = ?$$

Cette problematique n'est pas nouvelle par exemple pour trouver l'intersection de $x^2 +2$ et $x -1$ on pose:

$$ \begin{align}
    x^2+2 & = x-1 \\
    x^2 -x + 3 & = 0 \\
    x & = \frac{1\pm\sqrt{1^2-4\cdot1\cdot3}}{2\cdot1} \\
    x & = \frac{1\pm\sqrt{\color{red}{-11}}}{2}
\end{align} $$

À cette époque ce cas de figure voulait dire que les deux fonctions ne se coirsent jamais. Et effectivement dans notre cas, leselles ne se croisent pas:
<iframe src="https://www.desmos.com/calculator/f2g0w9gwfq?embed" width="500px" height="500px" style="border: 0px" frameborder=0></iframe>

Mais ce n'est pas toujours le cas...


## Problème de Cardano

Cardano et son disciple [Raphaël Bombelli](https://fr.wikipedia.org/wiki/Rapha%C3%ABl_Bombelli)(1526 - 1573) sont quoincés sur ce problème mais savent qu'il doit y avoir une solution <span style="color:red"> (Pourquoi? L'explication de la forme du plot de $x^3$ donnée dans la vidéo n'est pas valable chronologiquement parlant)</span> car le plot d'une fonction cubique passe toujours au moins une fois par l'axe des $x$:

<iframe src="https://www.desmos.com/calculator/403qr0hwzi?embed" width="500px" height="500px" solid #ccc" frameborder=0></iframe>


A ce stade, nous avons:
1. Une equation qui **doit** avoir une solution: $x^3 = 15x +4 \Rightarrow$ doit avoir une solution.
2. Une formule qui a prouvé qu'elle fonctionne: $x = \sqrt[3]{\frac{d}{2} + \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}} + \sqrt[3]{\frac{d}{2} - \sqrt{\frac{d^2}{4}-\frac{c^3}{27}}} \Rightarrow$ Sort une solution pour les equations cubiques
3. Cependant quand nous y injectons notre fonction on se retrouve dans une impasse à base de racines négatives $x = \sqrt[3]{2+\sqrt{\color{red}{-121}}} + \sqrt[3]{\color{red}{-121}}$


## Raphaël Bombelli
Il nous faudra une génération de plus pour commencer à faire de vrais progrès. Bombelli se dit que si ça ne fonctionne pas avec les positifs et que ça ne fonctionne pas avec les négatifs mais qu'il y a une solution, peut être qu'il y a un autre type de nombres qui nous amène à une solution.

Il adopte une approche pratique pour ne pas se compliquer à chercher un nom et un symbole pour cet éventuel nouveau type de nombres il décida simplement de laisser les racines négatives être des... racines négatives. 

> L'innovation ici est que ses contemporains pensent que les racines négatives ne peuvent pas exister, qu'elles n'ont pas de sense (À l'exception de Cardano, son mentor).

Bombelli se dit que si il étend le système numérique **comme cela avait été fait plusieurs fois** auparavant (décimaux, entiers relatifs... A chaque nouvel ensemble de nombre vient d'une nécessité à résoudre a nouveau problème) il pourrait résoudre le problème des racines négatives.