---
layout: post
title: "Analyse: Décomposition de fonction"
subtitle: ""
date: 2017-11-15
author: Sol
category: Analyse
tags: ""
finished: false
mathjax: true
---


## Exemple

$$\begin{align}
    f: \quad & \pmb{\mathbb{R}} \longrightarrow \pmb{\mathbb{R}} \\ 
    & x \longmapsto y =f(x) = \frac{2x+3}{1-4x}
\end{align}$$

<br>

$$ \Rightarrow f(x) = -\frac{1}{4x+1}\cdot \frac{7}{2}-\frac{1}{2} $$

### Décomposition en fonctions simples:

---

$$ \color{blue}{g_1(x)}=-\frac{1}{x} $$

$$ \small{\color{gray}{(\text{Symétrie d'axe }0y \text{ par rapport à la fonction de référence } \frac{1}{x})}} $$

<div>
    <iframe src="https://www.desmos.com/calculator/qzd1xpdk9n?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>

---

$$ \text{Compression horizontale de facteur 4} $$

$$ \color{red}{g_2(x)} = g_1(4x) = -\frac{1}{4x}$$


<div>
    <iframe src="https://www.desmos.com/calculator/k84dk3lmcm?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>

---

$$ \text{Shift horizontal de } - \frac{1}{4} $$

$$\color{green}{g_3(x)} = g_2 \left( x+\frac{1}{4} \right) = - \frac{1}{4\cdot(x+\frac{1}{4})}= - \frac{1}{4x+1}$$

<div>
    <iframe src="https://www.desmos.com/calculator/tzd549vscm?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>

---

$$ \text{Compression verticale de facteur } -\frac{7}{2} \quad (\; = \; \text{Décompression verticale de facteur } \frac{7}{2}) $$

$$ \color{orange}{g_4(x)} = g_3(x)\cdot \frac{7}{2} = - \frac{1}{4x+1} \cdot \frac{7}{2} $$

<div>
    <iframe src="https://www.desmos.com/calculator/fqtnzi0rsc?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>

---

$$ \text{Shift vertical de } -\frac{1}{2} $$

$$ \color{purple}{g_5(x)} = g_4(x) - \frac{1}{2} = - \frac{1}{4x+1} \cdot \frac{7}{2} - \frac{1}{2} = f(x) $$

<div>
    <iframe src="https://www.desmos.com/calculator/j0y89eoiqq?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>

---

$$ \color{red}{f(x)} = - \frac{1}{4x+1} \cdot \frac{7}{2} - \frac{1}{2} $$

<div>
    <iframe src="https://www.desmos.com/calculator/o8bwyog114?embed" width="500px" height="500px" style="border: 0px solid"></iframe>
</div>


### Conclusion

La forme généralisée de cette fonction est:

$$ A \cdot (\omega x - \varphi) + b $$

Avec:

* $A$: Compression verticale ($\equiv$ Amplitude)
* $\omega$: Compression horizontale
* $\varphi$: Shift horizontal ($\equiv$ Déphasage)
* $b$: Shift vertical