---
layout: post
title: "Algèbre: Ensembles de nombres"
subtitle: ""
date: 2017-09-19
author: Sol
category: Algebre
tags: ""
finished: false
mathjax: true
---

## Théorie élémentaire
On travail en mathématique avec différents ensembles de nombres:

### Entiers naturels $\pmb{\mathbb{N}}$
$$\pmb{\mathbb{N}} = \{0,1,2,3,...\}$$
$$\pmb{\mathbb{N}}^* = \pmb{\mathbb{N} \setminus \{0\} = \{1,2,3,...\}}$$

### Entiers relatifs $\pmb{\mathbb{Z}}$
$$\pmb{\mathbb{Z}} = \{...,-3,-2,-1,0,1,2,3,...\}$$
$$\pmb{\mathbb{Z}}^* = \pmb{\mathbb{Z}}\setminus \{0\}$$
Les éléments de $\pmb{\mathbb{Z}}$ correspondent aux graduations d'une droite graduée toutes les unités.

### (Décimaux $\pmb{\mathbb{D}}$)
Un nombre décimal est le quotient d'un entier relatif par une puissance de 10: $a/10^n$, par exemple $32/100$ mais aussi $3/5=6/10$. Les nombres décimaux sont ceux qui ont une écriture décimale **finie** (non-periodique).

### Rationnels $\pmb{\mathbb{Q}}$
$$\pmb{\mathbb{Q}} = \{\frac{a}{b} | a \in \pmb{\mathbb{Z}}, b \in \pmb{\mathbb{Z}}^*\}$$
Un nombre rationnel est le quotient $a/b$ d'un entier relatif $a$ par un entier naturel non nul $b$. Les nombres rationnels sont ceux qui ont une écriture décimale **periodique**.

### Réels $\pmb{\mathbb{R}}$
$$\pmb{\mathbb{R}}=\pmb{\mathbb{Q}}\cup\{...,\pi,e,\sqrt[2]{2},...\}$$
> $\{...,\pi,e,\sqrt[2]{2},...\} =$ **irrationnels**: Les nombres qui ne peuvent pas être mis sous forme de fraction

C'est l'ensemble de tous les nombres usuels. Les réels correspondent aux abscisses possibles d'un point sur une droite graduée. Les nombres réels qui ne sont pas rationnels sont appelés **irrationnels**. Parmi eux, on trouve $\pi$ ou $\sqrt{2}$.

### Ensemble vide $\emptyset$
Cet ensemble est inclus dans tous les autres ensembles


### Relations

$$\emptyset \subset \pmb{\mathbb{N}}\subset \pmb{\mathbb{Z}} \subset \pmb{\mathbb{D}} \subset \pmb{\mathbb{Q}} \subset \pmb{\mathbb{R}}$$

Ces différents ensembles de nombres sont inclus les uns dans les autres suivant le schéma suivant :

![alt](http://www.bibmath.net/dico/e/images/ensemblesnombres1.png)

-----
#### Exemple
![alt](/01illustrations/00EnsemblesNb/ensembles.png)

$x_1 \in A$
$x_2 \in B$
$x_3 \in A \cap B$

### Produit cartésien de deux ensembles
$$A \times B = \{(x, y) | x \in A, y \in B \}$$

C'est à dire l'ensemble de tous les **couples** possible obtenu en prenant un élément dand $A$ suivi d'un élément dans $B$, **dans cet ordre**. $ \Rightarrow $ donc $ \color{red}{A \times B \neq B \times A} $ !!

#### Exemple:
Soit les ensembles $A = \{1, 2\}$ et $B = \{a, b, c\}$

$Z = A \times B = \{1a, 1b, 1c, 2a, 2b, 2c\}$

#### Plan cartésien
Le produit cartésien de $\pmb{\mathbb{R}}$ par $\pmb{\mathbb{R}}$ est noté $\pmb{\mathbb{R}}^2 = \pmb{\mathbb{R}} \times \pmb{\mathbb{R}}$ (tous les couples de 2 nombres réels). Il est alors mis en relation avec un plan.

![alt](/01illustrations/00EnsemblesNb/plan.png)

### Les intervales


$$\begin{align}
    \text{Sur }\pmb{\mathbb{R}} & : x \in [a,b] \color{blue}{\text{ si }} a \le x \le b \color{blue}{\text{ intervalle } \color{red}{ \text{fermé}}} \\ 
    & x \in [a,b[ \color{blue}{\text{ si }} a \le x < b \color{blue}{\text{ intervalle } \color{red}{ \text{ouvert à droite}}} \\ 
    & x \in ]a,b[ \color{blue}{\text{ si }} a < x < b \color{blue}{\text{ intervalle } \color{red}{ \text{ouvert}}} \\ 
\end{align}$$

>Comme $+ \infty $ et $-\infty$ n'appartiennent pas à $\pmb{\mathbb{R}}$ on notera $ \pmb{\mathbb{R}} = ]-\infty, +\infty[$