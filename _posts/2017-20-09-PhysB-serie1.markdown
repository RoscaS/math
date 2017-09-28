---
layout: post
title: "Physique B(1): Electrostatique: notion de charge et loi de Coulomb"
subtitle: "Notion de charge et loi de Coulomb"
date: 2017-09-20
author: Sol
category: Physique-B
tags: "physique electrostatique"
finished: true
mathjax: true
---

# Notion Charge

Il existe une caractéristique appelée **charge** qui sont de deux types:
* Positives
* Negatives

Deux charges de **même signe se repoussent**, deux charges de **signe opposé s'attirent**.

## Provenance
**Atome**: Noyau central contenant:
* Protons: Chargé positivement
* Neutrons: Non-chargés
* Electrons: Charge positive

> Un atome est dit **neutre** si il possède autant de protons que d'électrons

> On Appelle **ion** tout atome (ou molécule) qui a plus (ou moins) d'électrons que de protons.

Par frottement, des électrons passent d'un corp à l'autre produisant ainsi des ions.
* Un corp chargé positivement a un déficite d'électrons 
* Un corp chargé négativement a un excédent d'électrons

## Charge élémentaire et Quantification
La charge élémentaire qui permet la quantification d'une charge se note $\pmb{e}$

$$ \bbox[5px,border:1px solid red]
    {e = 1,602\cdot10^{-19}C}
$$

Où $C$ est l'abréviation de _coulomb_, l'unité SI de la charge électrique.

* Charge du proton: $\bbox[5px,border:1px solid red] {q_p = +e}$
* Charge de l'électron: $\bbox[5px,border:1px solid red] {q_e = -e}$

## Conservation de la charge

> La charge électrique n'est ni créée, ni détruite, elle se transmet simplement d'un corp à l'autre.
> Benjamin Franklin

Autrement dit, la charge totale d'un système isolé reste constante.

**Exemple**: Les réactions chimiques; dans le cas suivant, deux molécules d'eau se transforment en un ion positif et un ion négatif:$\quad 2H_2 O \Rightarrow H_3 O^+ + HO^-$

## Loi de Coulomb

Soit deux charges bonctuelles $q_1 \text{ et } q_2$ séparées par une distance $d$.

L'intensité de la force électrique s'exerçant entre ces deux charges est donnée par:

$$
\bbox[5px,border:1px solid red]
    {F = \frac{1}{4\pi\epsilon_0} \frac{|q_1\;q_2|}{d^2}}
$$

Où $\epsilon_0 = 8,8542\cdot10^{-12}C^2 N^{-1} m^{-2}$ qui est la **constante de permitivité du vide**

> Loi établie en 1785 par le physicien français Charles de Coulomb

Cette formule peut être remplacée par:

$$\bbox[5px,border:1px solid red] {F = k_C \frac{|q_1\;q_2|}{d^2}}$$

Où $K_c$ est la constante de Coulomb et vaut approximtivement $ 9\cdot10^{9}$

### Remarques

* Les deux charges subissent des forces de même intensité (3e loi de Newton: Action-réaction)
* La direction des forces est donnée par la droite reliant les (**centre des**) deux charges ponctuelles (forces **radiales**, de symetrie **sphérique**).
* Les forces sont attractives (répulsives) si les deux charges sont de signe opposé (ont le même signe).
* La loi de Coulomb reste valable pour des objets dont la charge est répartie uniformément sur une surface sphérique ($d$ est la distance entre les centres des sphères).
* Si la taille des deux charges est petite par rapport à la distance qui les séparem la loi de Coulonb est une bonne approximation de la force entre ces charges.

>Si la taille des deux charges est petite par rapport à la distance qui les sépare, la loi de Coulomb est une bonne approximation de la force entre ces charges, sinon intégration nécessaire, donc division de l’objet en segments ponctuels, puis addition des forces que ces segments produisent individuellement


---

# Série associée

## 1.1
>Lors d'un orage, la foudre peut transporter une charge de $20C$ d'un nuage à la terre. À combien d'électrons environ correspond cette charge?

$$n_e = \frac{Q}{e} \approx 1,248 \cdot10^{20} $$

## 1.2
>À l’extérieur du noyau atomique, le neutron n est une particule instable et se désintègre en un proton p, un électron e− et un antineutrino:$\quad n \rightarrow p + e^- + \overline{v}$
Déterminer la charge électrique de l’antineutrino.

Comme la particule est maintenant dans un état d'équilibre et que nous savons que le proton possède une charge positive, l'electron une charge négative et que le neutron a une charge nulle, l'antineutrino possède forcément une **charge nulle** également.

## 1.3
>Dans un cumulonimbus se trouvent deux charges, l’une de +40 C et l’autre de −40 C, distantes de 5 km environ. En supposant que ces charges sont ponctuelles, calculer l’intensité de la force électrique FE qu’elles exercent l’une sur l’autre.

$$ F_e = k \frac{|Q_1 Q_2|}{d^2} \approx 5,76 \cdot 10^5 N$$

## 1.4
>Dans un atome d’hydrogène, l’électron et le proton sont distants de $d = 0,53 \cdot 10^{−10}$ m. Déterminer le rapport de $F_G$ sur $F_E$, où $F_G$ et $F_E$ sont respectivement la force graviﬁque et la force électrique agissant entre les deux particules. Les masses du proton et de l’électron sont respectivement $m_p = 1,6726 \cdot 10^{−27} \text{kg}$ et $m_e = 9,1095·10^{−31} kg$.

$q_{proton} = e$
$q_{electron} = -e$

$$ \frac{F_G}{F_E} = \frac{G\;m_1\;m_2}{d^2} \cdot \frac{d^2}{k\;e^2} = \frac{G\;m_1\;m_2}{k\;e^2} \approx 4,401 \cdot 10^{-40}$$

## 1.5
>Supposons que l’on donne une charge Q à la Terre et une même charge Q à la Lune. Quelle devrait être la valeur de Q pour que la force de répulsion électrique entre la Terre et la Lune soit égale à la force d’attraction gravitationnelle qui s’exerce entre les deux astres? Les masses de la Terre et de la Lune sont respectivement $mT = 5,9742 \cdot 10^{24} kg$ et   $mL = 7,350 \cdot 10^{22} kg$.

$Q_T = Q_L = Q$

$$\begin{align}
    \frac{kQ^2}{d^2} &= \frac{Gm_1m_2}{d^2} \\ 
    kQ^2 & = G m_1 m_2\\
    Q &= \sqrt{\frac{G m_T, m_L}{k}}{} \\
\end{align}$$

$$ \Rightarrow Q \approx 5,706 \cdot 10^{13}C $$
